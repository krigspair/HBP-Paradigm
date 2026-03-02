# HBP Hardware Architecture v0.1  
**Биологический субстрат психопатологии: от нейромедиаторов до микробиома**

**Module**: И-2 (Интеграция)  
**Date**: 01.03.2026  
**Authors**: Deep Research Team  
**Target**: Integration into HBP_System_Map_v1.4

---

## 0. Executive Summary

Парадигма HBP (Human Being Psychology) основана на Free Energy Principle и термодинамике диссипативных структур. Этиологическая триада (Постулат 6) выделяет три источника патогенеза: **Hardware failure** (субстрат), **Input failure** (среда) и **Software failure** (интериоризированный код). До настоящего момента Hardware-уровень был описан лишь фрагментарно, единственным детализированным мостом служила двухстадийная катехоламиновая модель депрессии Когана Б.М. и Дроздова А.З. (2013)[cite:31].

Данный документ представляет полную **Hardware Architecture** для HBP, структурированную в 7 слоёв:
1. **H-1 Нейромедиация** — дофамин, серотонин, норадреналин как регуляторы precision в FEP-иерархии
2. **H-2 Нейроиммунология** — кинурениновый путь, цитокины, ГПУВ Крыжановского как persistent prediction error
3. **H-3 Нейроэндокринология** — HPA-ось, allostatic load McEwen, CAR как биомаркер NESS breakdown
4. **H-4 Интероцепция** — interoceptive inference (Seth), поливагальная теория (Porges), HRV как индекс vagal tone
5. **H-5 Эпигенетика** — FKBP5/NR3C1/BDNF метилирование (Meaney, Yehuda), трансгенерационная передача травмы
6. **H-6 Ось кишечник-мозг** — психобиотики (Cryan & Dinan), SCFAs, вагальная сигнализация, dysbiosis → нейровоспаление
7. **H-7 Глимфатическая система / Митохондрии / Нейростероиды** — sleep-active clearance, ATP-дефицит, allopregnanolone как HPA-модулятор

Для каждого слоя определены:  
- **Механизм** на уровне субстрата  
- **Ключевые авторы** (западные / российские / азиатские школы)  
- **Мост к FEP** (precision, generative model, active inference, prediction error)  
- **Мост к HBP** (постулаты, 6 FM, CFR, термодинамика Part XXII)  
- **APV-карточки** (Assumption-Prediction-Validation) с Tier-разметкой  
- **Перекрёстные связи** между слоями (H-1↔H-2↔...↔H-7)

**Ключевой вывод**: Hardware failure не является автономным — он находится в bidirectional coupling с Input и Software. Клинические импликации для D-HBP: фармакотерапия требуется при декомпенсации Hardware (blunted CAR, QUIN/KYNA >2.0, IL-6 >10 pg/mL, HRV <40 ms RMSSD), тогда как при сохранном Hardware приоритетом остаётся психотерапия (CFR, attentional reallocation, relationship repair).

---

## 1. H-1: НЕЙРОМЕДИАЦИЯ

### 1.1 Механизм

Нейромедиаторы (neurotransmitters) — эндогенные сигнальные молекулы, обеспечивающие синаптическую передачу. Ключевые системы:  
- **Дофамин (DA)** — вентральная tegmental area (VTA), substantia nigra → nucleus accumbens, striatum, префронтальная кора  
- **Серотонин (5-HT)** — raphe nuclei → широкая проекция на кору, лимбическую систему, гипоталамус  
- **Норадреналин (NE)** — locus coeruleus → кора, гиппокамп, cerebellum  
- **Глутамат** — основной возбуждающий медиатор, NMDA/AMPA рецепторы  
- **ГАМК (GABA)** — основной тормозной медиатор  

**Якорь: модель Когана–Дроздова (2013)**[cite:31]. Двухстадийная катехоламиновая модель депрессии:  
1. **Компенсированная стадия** — периферическая гиперактивация симпато-адреналовой системы (↑ NE, ↑ адреналин), центральная активность сохранена, клиническая картина: тревога, ажитация, соматические симптомы.  
2. **Декомпенсированная стадия** — истощение центральных катехоламиновых депо (↓ DA, ↓ NE в ЦНС), периферическая активность парадоксально снижается, клиническая картина: ангедония, психомоторная заторможенность, когнитивный дефицит.

На языке HBP: **компенсация = NESS (Non-Equilibrium Steady State) под нагрузкой**, **декомпенсация = Critical Slowing Down → Attractor trapping** (термодинамика Part XXII)[cite:31][cite:32].

**Berridge & Robinson (incentive salience theory)**[cite:64][cite:67][cite:70][cite:72][cite:75]:  
- **Wanting** (мотивация) — дофамин-зависимо, nucleus accumbens  
- **Liking** (гедония) — опиоидные µ-рецепторы, ventral pallidum  
- **Learning** — ассоциативная память, amygdala, префронтальная кора  

Ключевое наблюдение: при депрессии DA-система hyporeactive → ↓ wanting, но liking может быть относительно сохранён (anhedonia ≠ absence of pleasure capacity, а = absence of motivation to pursue reward).

**DA как precision over policies** (FitzGerald, Dolan & Friston, 2015)[cite:46][cite:49][cite:56][cite:63]:  
В рамках Active Inference дофамин кодирует не абсолютную reward prediction error (классическая модель Schultz), а **уверенность (precision) в выборе policy** (последовательности действий). ↓ DA → снижение precision → behavioral exploration collapse → rigidity, апатия.

**Российская школа**:  
- **Судаков К.В.** (2011)[cite:113]: эмоции как информационные эквиваленты потребностей в архитектуре функциональных систем (Анохин П.К. → Судаков). Эмоции = оценка рассогласования между акцептором результата действия и реальным афферентным сигналом. Положительные эмоции → подкрепление, отрицательные → переход к новой функциональной системе.  
- **Ашмарин И.П.** (1996)[cite:114][cite:117][cite:120]: теория каскадной пептидной регуляции. Нейропептиды (субстанция P, энкефалины, нейротензин) действуют как модуляторы классических нейромедиаторов, обеспечивая fine-tuning синаптической передачи. Концепция "синактонов" — функциональных ансамблей нейромедиатор + нейропептид.  
- **Крыжановский Г.Н.** (ГПУВ — генераторы патологически усиленного возбуждения)[cite:115][cite:118][cite:121]: агрегат гиперактивных нейронов, продуцирующий неконтролируемый поток импульсов в условиях недостаточности тормозного контроля. ГПУВ = Hardware substrate of pathological attractor (в терминологии HBP).

### 1.2 Ключевые авторы

**Западная школа**:  
- Berridge K.C., Robinson T.E. (2016) "Liking, wanting, and the incentive-sensitization theory of addiction"[cite:64][cite:67][cite:70][cite:72][cite:75]  
- FitzGerald T.H.B., Dolan R.J., Friston K.J. (2015) "Dopamine, reward learning, and active inference"[cite:46][cite:49][cite:56][cite:63]  
- Schultz W. (2015) "Neuronal reward and decision signals: from theories to data" *Physiological Reviews*  

**Российская/советская школа**:  
- Коган Б.М., Дроздов А.З. (2013) "Двухстадийная катехоламиновая модель депрессивных расстройств" *Социальная и клиническая психиатрия*[cite:31][cite:32][cite:35][cite:39]  
- Судаков К.В. (2011) "Эмоции в системной организации поведенческих актов" *Успехи современной биологии*[cite:113]  
- Ашмарин И.П., Стукалов П.В. (1996) "Нейрохимия" Учебник[cite:114][cite:117][cite:120]  
- Крыжановский Г.Н. (1997) "Генераторы патологически усиленного возбуждения" *Патологическая физиология*[cite:115][cite:118][cite:121]

**Азиатская школа**:  
Прямых публикаций по catecholamine depression model не обнаружено. Азиатские исследования сосредоточены на downstream effects (kynurenine pathway — см. H-2).

### 1.3 Мост к FEP

В FEP-иерархии нейромедиаторы выполняют роль **модуляторов precision** (expected precision of prediction errors)[cite:46][cite:49][cite:56]:

| Нейромедиатор | FEP-функция | Эффект при дефиците |
|---------------|-------------|---------------------|
| **Дофамин (DA)** | Precision over policies (confidence in action selection) | ↓ DA → low confidence → behavioral inhibition, anhedonia |
| **Серотонин (5-HT)** | Precision over aversive predictions (punishment sensitivity) | ↓ 5-HT → hyperreactivity to negative feedback, rumination |
| **Норадреналин (NE)** | Precision over unexpected uncertainty (volatility encoding) | ↓ NE → impaired adaptation to changing environments |
| **Ацетилхолин (ACh)** | Precision over expected uncertainty (attention modulation) | ↓ ACh → cognitive inflexibility, attentional deficits |

**Ключевой момент**: нейромедиаторная дисфункция = **дисрегуляция precision-weighting** на разных уровнях иерархии generative model. Это не просто "химический дисбаланс", а нарушение способности мозга оценивать надёжность своих прогнозов.

**Модель Когана-Дроздова в FEP-терминах**:  
- **Компенсированная стадия**: система поддерживает высокий precision over arousal (гиперактивация NE), но это энергетически затратно → накопление allostatic load.  
- **Декомпенсированная стадия**: precision collapse → генеративная модель больше не может минимизировать prediction error → attractor rigidity (депрессивный паттерн становится self-sustaining).

### 1.4 Мост к HBP

**Постулаты**:  
- **Постулат 3** (Аффект = interoceptive inference): нейромедиаторы модулируют интероцептивные prediction errors → изменение аффективной валентности.  
- **Постулат 6** (Этиологическая триада): H-1 failures (катехоламиновый коллапс) могут быть первичными (Hardware failure) или вторичными (Software failure → хроническое избегание → downregulation DA-рецепторов).  
- **Постулат 9** (CFR — Continuous Fractal Reframing): фармакотерапия (SSRI/SNRI) = Hardware repair, но без Software/Input изменений рецидив вероятен.

**6 FM (Fundamental Motivations)**:  
- **FM1 (Бытие-в-мире / Umwelt)**: ↓ DA → anhedonia → мир теряет "привлекательность" (incentive salience ↓)  
- **FM2 (Жизнь / vitality)**: ↓ NE → психомоторная заторможенность  
- **FM4 (Смысл / meaning)**: хроническое ↓ DA → "everything is meaningless" (экзистенциальная пустота как downstream от Hardware failure)

**CFR-техника "Reframing через биологическую легитимацию"**: клиент: "Я слабак, не могу заставить себя действовать" → терапевт: "Ваш мозг сейчас в состоянии, аналогичном декомпенсированной стадии по модели Когана-Дроздова — это не слабость, а временная Hardware дисфункция, требующая комбинированного вмешательства (фармакотерапия + behavioral activation)."

**Термодинамика (Part XXII)**:  
Компенсация→декомпенсация = фазовый переход из одного аттрактора в другой. Critical Slowing Down: система замедляет recovery после возмущений (resilience ↓) → малейший стрессор вызывает сильное отклонение → eventual collapse в pathological attractor.

### 1.5 APV-карточка: DA Precision & Behavioral Activation

**APV-1.1: Дофамин как предиктор response на behavioral activation**

- **A** (Assumption): Пациенты с декомпенсированной стадией депрессии (по Коган-Дроздов) имеют сниженный striatal DA release в ответ на reward cues, что предсказывает poor response на изолированную behavioral activation (BA) без фармакотерапии.

- **P** (Prediction): MDD пациенты (n≥60) с [11C]-raclopride PET DA release <15% в nucleus accumbens при anticipatory reward task покажут ΔM-BDI <20% после 8 недель BA, тогда как пациенты с DA release >15% покажут ΔBDI >35%.

- **V** (Validation):  
  - Дизайн: prospective cohort  
  - Выборка: MDD, HAM-D ≥18, drug-naïve  
  - Инструменты: [11C]-raclopride PET, monetary incentive delay task, 8-week BA protocol, weekly BDI-II  
  - Контроль: age, sex, baseline BDI-II, comorbid anxiety

- **Status**: Not tested (гипотеза HBP-novel)

- **Tier**: T3 (HBP-novel prediction, требует PET-инфраструктуры)

### 1.6 Перекрёстные связи

| H-1 → | Механизм | Источник |
|-------|----------|----------|
| **H-2 Нейроиммунология** | ↓ DA → microglial activation (DA D2 receptors на микроглии подавляют воспалительный ответ) | [cite:105] |
| **H-3 Нейроэндокринология** | DA ингибирует CRH release в PVN → ↓ DA → ↑ HPA activation | [cite:138] |
| **H-4 Интероцепция** | DA modulates precision over interoceptive predictions (insula) | [cite:170] |
| **H-6 Gut-Brain** | Gut bacteria (Lactobacillus plantarum) продуцируют DA precursors → ↑ peripheral DA (но BBB не пересекает) | [cite:229] |
| **H-7 Glymphatic/Mito** | Sleep deprivation → ↓ DA receptor availability (compensatory downregulation) | [cite:293] |

---

## 2. H-2: НЕЙРОИММУНОЛОГИЯ

### 2.1 Механизм

**Кинурениновый путь (Kynurenine pathway, KP)** — основной маршрут метаболизма триптофана (TRP) в ЦНС (95% TRP)[cite:77][cite:78][cite:81]:

```
Триптофан (TRP)  
    ↓ IDO/TDO (indoleamine 2,3-dioxygenase / tryptophan 2,3-dioxygenase)  
Кинуренин (KYN)  
    ↙                ↘  
KAT (kynurenine        KMO (kynurenine 3-monooxygenase)  
aminotransferase)      3-hydroxykynurenine (3-HK)  
    ↓                       ↓  
Кинуреновая            Хинолиновая кислота (QUIN)  
кислота (KYNA)          ↓  
(neuroprotective,       NMDA agonist → excitotoxicity  
NMDA antagonist)        oxidative stress, apoptosis
```

**Ключевые дисбалансы при депрессии**[cite:95][cite:97]:  
- ↑ QUIN (quinolinic acid) — нейротоксический метаболит, NMDA receptor agonist  
- ↓ KYNA (kynurenic acid) — нейропротективный, NMDA antagonist  
- **QUIN/KYNA ratio >2.0** — маркер эксайтотоксичности  

**Активация IDO** происходит под действием провоспалительных цитокинов (IL-6, TNF-α, IFN-γ)[cite:83][cite:98][cite:99]. Хроническое воспаление → sustained IDO activation → depletion TRP (↓ 5-HT synthesis) + ↑ neurotoxic QUIN.

**Цитокиновая гипотеза депрессии**[cite:96][cite:99][cite:102][cite:105]:  
- ↑ IL-6, TNF-α, IL-1β в крови и CSF у MDD пациентов  
- Anti-inflammatory cytokines (IL-10) снижены или соотношение pro/anti смещено  
- Meta-analysis (Dowlati et al., 2010): IL-6 и TNF-α elevated в 60-70% MDD studies  

**Sickness behavior** (Dantzer, 2009)[cite:91]: поведенческие симптомы острой инфекции (летаргия, ангедония, социальная withdrawal, потеря аппетита) аналогичны депрессии. Dantzer: это не патология, а **adaptive active inference** — организм минимизирует prediction error при инфекции через снижение активности (энергосбережение для иммунной борьбы). Но при хроническом воспалении эта адаптация становится maladaptive → клиническая депрессия.

**Российская школа: ГПУВ Крыжановского**[cite:115][cite:118][cite:121][cite:127]:  
Генераторы патологически усиленного возбуждения (ГПУВ) — агрегат гиперактивных нейронов, продуцирующий неконтролируемый поток импульсов. Возникает при:  
1. Прямом повреждении нейронов (например, эксайтотоксичность от QUIN)  
2. Недостаточности тормозного контроля (↓ GABA, ↓ KYNA как NMDA antagonist)  

ГПУВ = нейрональный субстрат **патологической системы** (Крыжановский) = в HBP-терминах **pathological attractor** с positive feedback loops.

**Азиатская школа**:  
- Yamamoto Y., Saito K. (Fujita Health University, Japan, 2020)[cite:255]: serum anthranilic acid (AA) — метаболит кинуренинового пути — elevated у high-risk MDD пациентов. AA может служить early biomarker.  
- KAIST (Korea, 2025)[cite:257][cite:260][cite:263]: optogenetic modulation FGFR1 signaling в dentate gyrus восстанавливает антидепрессивные эффекты. Связь с нейровоспалением: FGFR1 downregulation при хроническом стрессе → ↓ neurogenesis → vulnerability к депрессии.  
- Chinese studies (Central South University, 2024)[cite:259]: integrated gut metabolome + brain fNIRS показывает связь между gut dysbiosis, KYN metabolites и cognitive decline у elderly.

### 2.2 Ключевые авторы

**Западная школа**:  
- Dantzer R. (2009) "Cytokine, sickness behavior, and depression" *Immunology and Allergy Clinics of North America*[cite:91]  
- Savitz J. (2020) "The kynurenine pathway: a finger in every pie" *Molecular Psychiatry*[cite:81]  
- Raison C.L., Miller A.H. (2013) "Role of inflammation in depression" *Neuropsychopharmacology*[cite:83]  
- Miller A.H., Raison C.L. (2016) "The role of inflammation in depression: from evolutionary imperative to modern treatment target" *Nature Reviews Immunology*[cite:99]

**Российская школа**:  
- Крыжановский Г.Н. (1997) "Генераторы патологически усиленного возбуждения в патогенезе неврологических расстройств" *Патологическая физиология и экспериментальная терапия*[cite:115][cite:118][cite:121][cite:127]

**Азиатская школа**:  
- Yamamoto Y., Saito K. (2020) "Serum metabolic profiles of the tryptophan-kynurenine pathway in high risk MDD" *Scientific Reports* (Fujita Health University, Japan)[cite:255]  
- Heo W., KAIST (2025) "FGFR1 signaling in depression: optogenetic rescue" *Experimental & Molecular Medicine* (Korea)[cite:257][cite:260][cite:263][cite:269]  
- Jiao B. et al. (2024) "Integrated gut metabolome-microbiome-brain fNIRS" *Gut Microbes* (Central South University, China)[cite:259]

### 2.3 Мост к FEP

Chronic inflammation = **persistent interoceptive prediction error**[cite:170][cite:183]:  
- Цитокины (IL-6, TNF-α) активируют vagal afferents → ascending interoceptive signal  
- Insula (primary interoceptive cortex) генерирует prediction: "организм в норме"  
- При хроническом воспалении: prediction systematically fails → high precision на prediction error → **allostatic overload** (см. H-3)  

**QUIN как excitotoxic agent** → нарушение glutamate homeostasis → impaired neural plasticity → generative model rigidity. В FEP-терминах: NMDA-опосредованная excitotoxicity = excessive synaptic pruning → loss of model complexity → oversimplified generative model → inflexibility.

**Sickness behavior (Dantzer) в FEP-framework**[cite:91]:  
Организм при инфекции обновляет свою generative model: "моё состояние = under immune challenge, поэтому оптимальная policy = rest, не explore". Это adaptive inference. Но при хроническом воспалении update persists → chronic low-arousal policy → клиническая депрессия.

### 2.4 Мост к HBP

**Постулаты**:  
- **Постулат 3** (Аффект = interoceptive inference): хроническое воспаление → sustained negative interoceptive signal → dysphoric affect  
- **Постулат 6** (Этиологическая триада):  
  - **Hardware failure**: genetic predisposition (e.g., IDO polymorphisms) → hyperactive kynurenine pathway  
  - **Input failure**: chronic psychosocial stress → ↑ cortisol → ↑ IDO activity  
  - **Software failure**: rumination patterns → sustained HPA activation → ↑ cytokines → positive feedback loop  

**6 FM**:  
- **FM2 (Жизнь)**: sickness behavior → withdrawal from vital activities  
- **FM3 (Самость)**: inflammatory cytokines cross BBB → direct effect на hippocampus (↓ BDNF, ↓ neurogenesis) → autobiographical memory disruption  
- **FM4 (Смысл)**: QUIN-induced excitotoxicity в prefrontal cortex → impaired abstract reasoning → "loss of meaning"

**CFR-техника "Reframing inflammation as adaptive"**: клиент: "Я не могу встать с кровати, я просто ленивый" → терапевт: "Ваш организм находится в режиме 'борьбы с воспалением', ваше тело посылает сигнал 'отдыхай' — это биологически осмысленная реакция, но она стала хронической. Нам нужно переключить систему из 'defence mode' в 'exploration mode'."

### 2.5 APV-карточка: QUIN/KYNA Ratio as Treatment Predictor

**APV-2.1: Кинурениновый дисбаланс предсказывает ответ на anti-inflammatory augmentation**

- **A**: MDD пациенты с elevated QUIN/KYNA ratio (>1.5) имеют treatment-resistant depression (TRD), обусловленную нейровоспалением, и покажут superior response на anti-inflammatory add-on (minocycline, NAC) по сравнению с monotherapy SSRI.

- **P**: RCT (n≥100): MDD с QUIN/KYNA >1.5 randomized в SSRI+minocycline vs SSRI+placebo. Primary outcome: remission rate (HAM-D ≤7) at 12 weeks. Predicted effect size: OR≥2.5 для augmented arm.

- **V**:  
  - Дизайн: double-blind RCT  
  - Выборка: MDD, HAM-D ≥18, ≥1 prior SSRI failure  
  - Инструменты: LC-MS/MS plasma KYN metabolites (baseline), HAM-D (weekly), neuropsychological battery (CANTAB)  
  - Контроль: baseline IL-6, CRP, BMI, smoking status

- **Status**: Partially confirmed (pilot studies показывают trend, но powered RCTs отсутствуют[cite:102])

- **Tier**: T2 (empirically grounded, но требуется replication)

### 2.6 Перекрёстные связи

| H-2 → | Механизм | Источник |
|-------|----------|----------|
| **H-1 Нейромедиация** | IL-6 → ↓ tetrahydrobiopterin (BH4) → ↓ TH activity → ↓ DA/5-HT synthesis | [cite:83] |
| **H-3 Нейроэндокринология** | IL-6 → CRH activation → HPA axis hyperactivity | [cite:99] |
| **H-4 Интероцепция** | Vagal afferents express TLR-4 → sense LPS → relay inflammatory signal to NTS | [cite:240] |
| **H-5 Эпигенетика** | Childhood trauma → IL-6 gene methylation → sustained inflammatory phenotype | [cite:210] |
| **H-6 Gut-Brain** | Gut dysbiosis → LPS translocation → systemic inflammation → ↑ IDO | [cite:235] |
| **H-7 Glymphatic** | Neuroinflammation → BBB disruption → ↓ glymphatic clearance → Aβ accumulation | [cite:282] |

---

[File continues — full content in repository]