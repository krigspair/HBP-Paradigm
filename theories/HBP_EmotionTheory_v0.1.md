# HBP Emotion Theory v0.1
## Парциальная теория эмоций (P-Emotion) в парадигме Human Being Psychology
**28.02.2026 | Модуль И-2 | TRL 2–3 (conceptual integration + partial literature evidence)**

---

## 0. ПОЗИЦИОНИРОВАНИЕ

### 0.1. Зачем HBP нужна теория эмоций?
System Map v1.4 содержит фрагменты: решение Barrett vs Panksepp (DR4), core affect в онтогенезе (XIII), DERS-18 в батарее, negative emotion words в L-HBP. Но нет связного ответа на вопросы:
- Что такое эмоция в онтологии HBP?
- Как эмоция соотносится с 6 измерениями бытия (FM1–FM6)?
- Как эмоция становится патогенной?
- Как терапия работает с эмоцией через precision re-weighting?

Настоящий документ закрывает этот гэп.

### 0.2. Привязка к ядру HBP
- Постулаты 1–3 (Being-as-Process, Substrate, Dual Description)
- Постулаты 4–5 (FEP, Active Inference)
- Постулат 6 (Dimensions of Being / 6 FM)
- Постулат 13 (Prediction Error → 3 канала)
- Этиология: Hardware / Input / Software failure
- Здоровье: CFR (Complexity–Flexibility–Resilience)

### 0.3. Связь с другими P-теориями
- **P-Aggression v1.0**: агрессия как частный случай explosion-mode эмоциональной динамики; flow/compression/explosion = эмоциональные организации
- **Personality Theory v0.1**: 4 параметра (Coherence, Flexibility, Congruence, Differentiation) — эмоциональная гранулярность = аспект Differentiation

---

## 1. ОНТОЛОГИЧЕСКИЙ СТАТУС ЭМОЦИИ В HBP

### 1.1. Ключевой тезис

> **Эмоция (emotion) — это способ проживания prediction error в теле; модус бытия (Befindlichkeit), а не информация «о» чём-то.**

Эмоция не «случается с субъектом» и не «вычисляется мозгом» — она есть **процесс**, в котором субъект обнаруживает себя в определённом отношении к миру. Это согласуется с:
- Постулат 1 (Being-as-Process): эмоция — аспект процесса бытия, а не его продукт
- Хайдеггер (Befindlichkeit): эмоция = настроенность, в которой бытие открывается
- Colombetti (primordial affectivity): все живые системы аффективны; аффект = sense-making
- Гендлин (felt sense): переживание = prediction error, ещё не разрешённый в категорию

### 1.2. Формальное определение через FEP

Эмоция формализуется как **многоуровневый интероцептивный inference**:

\[
\text{Emotion} = f(\text{PE}_{\text{intero}},\; \pi_{\text{intero}},\; \text{GM}_{\text{concept}},\; \text{context})
\]

где:
- PE_intero — интероцептивная prediction error (расхождение между предсказанным и реальным состоянием тела)
- π_intero — precision (точность), присвоенная интероцептивному сигналу
- GM_concept — концептуальный уровень генеративной модели (эмоциональные категории)
- context — ситуативный контекст (включая реляционное поле — Мясищев)

### 1.3. Что это НЕ

- Не «базовая эмоция» как дискретная сущность с фиксированной нейронной цепью (≠ классический Ekman)
- Не чисто когнитивная конструкция без телесного субстрата (≠ радикальный конструкционизм)
- Не побочный продукт когнитивной обработки (≠ Zajonc vs Lazarus в их крайних позициях)

---

## 2. АРХИТЕКТУРА: ТРЁХУРОВНЕВАЯ МОДЕЛЬ ЭМОЦИЙ HBP (HEA — Hierarchical Emotion Architecture)

### 2.1. Три уровня

| Уровень | Название | Содержание | Формализация (FEP) | Источник |
|---------|----------|------------|---------------------|----------|
| **L0** | Core Affect | Непрерывное интероцептивное предсказание: валентность + arousal | Valence = utility − E[utility] (Pattisapu, 2024); Arousal = H[Q(s|o)] — энтропия posterior beliefs | Russell (core affect), Barrett (allostasis), Pattisapu et al. 2024 |
| **L1** | Affective Priors | Эволюционно закреплённые генеративные модели: 7 систем Panksepp как hardcoded priors | Subcortical precision-weighting interoceptive PE (Solms, 2021) | Panksepp (7 систем), Solms (FEP-формализация) |
| **L2** | Emotion-as-Construal | Дискретная эмоция = категориальный inference поверх L0+L1 + контекст | Conceptual categorization via hierarchical GM (Smith, Lane, Parr, Friston, 2019) | Barrett (TCE), Izard (emotion schemas), Smith et al. 2019 |

### 2.2. Обоснование иерархии: почему это не эклектика

Barrett (2025) настаивает на «непримиримости» (irreconcilability) TCE и BET. HBP занимает **третью позицию**: иерархическая генеративная модель, где:

- L0 и L1 работают на **разных уровнях иерархии** GM — субкортикальный (PAG, VTA, hypothalamus) vs кортикальный (insula, ACC, mPFC)
- L2 — **концептуальный слой**, который категоризирует непрерывный L0-сигнал с помощью приобретённых категорий

Формальное обоснование — **deep active inference** (Hesp et al., 2021):
- **Affective charge (AC)** = Bayes-оптимальный терм обновления «subjective fitness» (субъективной пригодности модели)
- AC отслеживает *изменения* в оценках пригодности и придаёт знак (валентность) иначе беззнаковым расхождениям
- Агент с валентными репрезентациями может **превентивно** оптимизировать уверенность в выборе действий

Это позволяет одновременно:
- Сохранить hardcoded priors Panksepp (L1) как эволюционно стабилизированные паттерны precision allocation
- Принять конструкционистскую вариативность Barrett (L2) как свойство концептуального слоя
- Избежать «бифуркации природы» (Barrett, 2025) — L0/L1/L2 это не «тело vs разум», а уровни одной иерархии

### 2.3. Subjective Fitness ≈ Befindlichkeit

Ключевой мост вычислительное × феноменологическое:
- **Subjective fitness** (Hesp et al., 2021) = «внутренняя оценка общей пригодности модели действий»
- **Befindlichkeit** (Хайдеггер) = настроенность бытия, в которой Dasein всегда уже обнаруживает себя
- **Витальный аффект** (Stern) = доязыковое переживание жизненности

В HBP: **витальный аффект (L0 + L1) есть переживание субъективной пригодности (subjective fitness) генеративной модели бытия.**

---

## 3. ЭМОЦИЯ × 6 ИЗМЕРЕНИЙ БЫТИЯ (FM1–FM6)

Каждое измерение порождает специфический домен интероцептивного inference:

| FM | Ядерный вопрос | Эмоциональный домен | Ключевые эмоции | FEP-механизм | Hardcoded prior (L1) |
|----|---------------|---------------------|-----------------|--------------|---------------------|
| FM1: Бытие-в-мире | Могу ли я быть? | Базовая безопасность / угроза | Страх, базовое доверие, тревога | Precision на экстеро+интеро PE угрозы | FEAR, PANIC/GRIEF |
| FM2: Жизнь | Нравится ли мне жить? | Витальный аффект | Радость, горе, витальная энергия, отвращение | Valence = utility − E[utility]; subjective fitness | SEEKING, LUST, PLAY |
| FM3: Самость | Имею ли я право быть собой? | Самореференциальный аффект | Стыд, гордость, вина | Precision на self-model PE | RAGE (при фрустрации автономии) |
| FM4: Смысл | Что я должен делать? | Экзистенциальный аффект | Воодушевление, отчаяние, экзистенциальная тревога | EFE life-policies: hyper-priors о ценности | SEEKING (epistemic drive) |
| FM5: Бытие-в-цифре | Как я существую в Digitalwelt? | Дофаминергический цикл | Компульсивный интерес, FOMO, цифровая скука | Precision-trapping в scroll-loops; attenuated interoception | SEEKING (hijacked) |
| FM6: Бытие-в-конечности-мира | Как я встречаю конечность мира? | Трансцендентный аффект | Экологическая тревога, солидарность, terror | PE от осознания неопределённости мира; TMT | PANIC/GRIEF (расширенный) |

---

## 4. НАСТРОЕНИЕ (MOOD) КАК ГИПЕР-ПРАЙОР

### 4.1. Mood ≠ Emotion

Следуя Clark, Watson & Friston (2018):
- **Emotion** = ситуативный inference (секунды–минуты)
- **Mood** = гипер-прайор над неопределённостью (часы–дни): убеждения более высокого уровня, задающие тон для эмоциональных эпизодов

### 4.2. Depressive mood как locked-in hyper-prior

Депрессивное настроение = пессимистические гипер-прайоры, делающие систему нечувствительной к позитивному сенсорному контексту. В HBP-терминах: **ригидный аттрактор на уровне mood**, сужающий пространство эмоционального реагирования.

### 4.3. Mood × Emotion Schema (Izard)

Emotion schema Изарда (стабилизированное эмоция-когниция взаимодействие) = аттрактор в эмоциональном пространстве состояний. Малоадаптивная schema = ригидный аттрактор. Прямая изоморфность с патогенезом HBP.

---

## 5. ЭМОЦИОНАЛЬНАЯ ПАТОЛОГИЯ В HBP

### 5.1. Общий принцип

> **Эмоциональная патология = ригидный аттрактор в пространстве эмоциональных состояний, сужающий бытие.**

Симптом — лучшее решение системы при данных условиях (ядро HBP).

### 5.2. Таксономия через precision dysregulation

| Паттерн | Precision-механизм | Клинические проявления | Формат HBP |
|---------|-------------------|----------------------|------------|
| **Гиперточная интероцепция** (π_intero ↑↑) | Чрезмерно сильные ожидания телесных изменений → хронический PE | Тревога, паническое расстройство, соматоформные расстройства | S-HBP, D-HBP Level 1–2 |
| **Гипоточная интероцепция** (π_intero ↓↓) | Ослабленная precision на интероцептивном PE → неспособность дифференцировать аффект | Алекситимия, диссоциация, ПТСР (избегающий тип) | S-HBP (recalibration), D-HBP Level 2–3 |
| **Locked-in mood** (hyper-prior rigidity) | Пессимистические/тревожные гипер-прайоры нечувствительны к контексту | Депрессия, генерализованная тревога | D-HBP Level 2–3 |
| **Oscillating precision** (π chaotic) | Хаотическое переключение precision allocation | BPD — аффективная нестабильность, self-other mergence | D-HBP + C-HBP |
| **Collapsed inference** (contradictory priors) | Конфликтующие priors → нет когерентной политики | Дезорганизованная привязанность, структурная диссоциация | D-HBP Level 3, C-HBP |

### 5.3. Этиологическая привязка

- **Hardware failure** → нарушение субстрата интероцептивного inference (CAN damage, insular lesions, HPA-axis dysregulation)
- **Input failure** → среда не предоставила «wiring instructions» для precision calibration (Barrett, 2025: social allostasis); deprivация, abuse → искажённая precision allocation strategy
- **Software failure** → малоадаптивные emotion schemas (Izard) = ригидные аттракторы; интериоризированный код: «чувствовать X запрещено/опасно»

### 5.4. Эмоции × Потребности Рыжова

Фрустрация потребности (goal-directed theory, Moors 2022) → prediction error между prior preference (P_o^pref) и actual experience q(o):

\[
D_{KL}[q(o) \| P_o^{pref}] > \theta \implies \text{negative affective charge}
\]

Чем выше ценность потребности в иерархии, тем больше affective charge при фрустрации. 8 потребностей Рыжова = 8 доменов prior preferences, каждый со специфической эмоциональной сигнатурой при фрустрации (см. Part XXII, Table 22.3.2).

---

## 6. ЭМОЦИЯ × CFR (Complexity–Flexibility–Resilience)

### 6.1. Эмоциональная гранулярность как маркер CFR

- **Эмоциональная гранулярность** (emotion granularity / differentiation) = способность дифференцировать эмоциональные категории → показатель Complexity + Flexibility
- Низкая гранулярность → больше тревоги и депрессии (meta-evidence)
- Гранулярность изменяется под стрессом → динамический маркер
- В Personality Theory: гранулярность = аспект параметра **Differentiation**

### 6.2. Arousal как энтропия

Pattisapu et al. (2024): arousal = H[Q(s|o)] — энтропия апостериорных убеждений.
- Высокая энтропия → высокий arousal → высокая Complexity пространства состояний
- При патологии: энтропия может быть либо хронически высокой (тревога), либо хронически низкой (апатия) → в обоих случаях ↓ Flexibility

### 6.3. Аффективная инерция и вариабельность

Zavlis et al. (2025) формализовали три типа аффективной нестабильности:
- **Emotional rigidity** (инерция) = высокий autocorrelation → ↓ Flexibility
- **Emotional transience** (нестабильность) = высокая variance → ↓ Resilience
- **Emotional reactivity** (чрезмерная реактивность) = high coupling с внешними событиями → ↓ Resilience

Все три измеримы через EMA time-series — прямая связь с батареей HBP.

---

## 7. ЭМОЦИЯ × РАЗВИТИЕ

### 7.1. Онтогенез через HEA

| Возраст | L0 (Core Affect) | L1 (Affective Priors) | L2 (Emotion-as-Construal) |
|---------|-------------------|----------------------|---------------------------|
| 0–3 мес | Валентность + arousal, hardcoded | BIOS-уровень: FEAR, SEEKING, PANIC активны | Отсутствует |
| 3–12 мес | Калибровка через MAT (maternal affective touch → insular precision) | Attachment priors формируют precision allocation strategy | Широкие категории: позитивное/негативное |
| 1–3 года | Интероцептивная precision стабилизируется | IWM (internal working models) = relational priors | Happiness, sadness, anger (Widen & Russell, 2008) |
| 3–6 лет | ToM → самореферентные эмоции | Scaffolding: опекун обучает эмоциональным категориям | Fear, surprise, disgust добавляются |
| 6–12 | PFC-ингибиция → top-down regulation | Priors уточняются через социальный контекст | Полный репертуар; начало метакогниции |
| 12–25 | Мета-эмоциональное осознание | Гипер-прайоры (mood) стабилизируются | Высокая гранулярность (при благополучном развитии) |

### 7.2. Передача precision в диаде

- Cook (2025): интероцепция опекуна → интероцепция ребёнка → чувствительность к угрозе
- Barrett (2025): социальный аллостаз — опекун = внешний аллостатический регулятор
- MAT (2026): материнское аффективное прикосновение → C-tactile fibers → insular maturation → precision calibration

---

## 8. ЭМОЦИЯ × ТЕРАПИЯ: PRECISION RE-WEIGHTING КАК ЦЕНТРАЛЬНЫЙ МЕХАНИЗМ

### 8.1. Общий принцип

Терапевтическая работа с эмоциями в HBP = **precision re-weighting** — помощь пациенту в перевзвешивании точности интероцептивных vs экстероцептивных vs концептуальных сигналов.

### 8.2. Уровни precision re-weighting (расширение)

| Level | Механизм | Эмоциональная работа | Формат |
|-------|----------|---------------------|--------|
| 0 | Стабилизация субстрата | Восстановление базовой интероцептивной precision (сон, питание, HRV) | C-HBP, lifestyle |
| 1 | Mindfulness / awareness | Наблюдение за L0 (core affect) без категоризации → увеличение π_intero | M-HBP, B-HBP |
| 2 | Работа с priors | Дестабилизация ригидных emotion schemas (Izard); reconsolidation; концептуальное перекатегоризирование (L2) | D-HBP |
| 3 | Глубинная реструктуризация | Изменение гипер-прайоров (mood level); работа с Self → FM3; экзистенциальный уровень → FM4/FM6 | D-HBP depth |

### 8.3. Мосты к конкретным терапевтическим подходам

- **EFT (Greenberg)**: marker-guided tasks = работа с L2 (emotion schemas) через controlled PE → reconsolidation
- **Gendlin's Focusing**: felt sense = L0 PE, ещё не разрешённый в категорию L2; focusing = повышение π_intero
- **S-HBP / SE (Levine)**: recalibration интероцептивной precision через bottom-up PE (pendulation, titration)
- **D-HBP**: Level 2–3 — дестабилизация ригидных аттракторов через mismatch experience → фазовый переход
- **C-HBP**: Level 0 — фармакология как precision engineering (SSRI modulate serotonergic precision)

### 8.4. Integrative Model: Intero-Extero Arbitration

Модель 2025 (arXiv): precision-weighted arbitration в vmPFC/OFC между интеро- и экстероцептивными потоками:
- w → 1.0: перегруженная интероцепция = **тревога**
- w → 0: подавленная интероцепция = **ПТСР** (избегающий тип), **алекситимия**
- w ≈ 0.5: гибкий баланс = **здоровье**

Терапевтическая цель: восстановить **гибкий арбитраж** (flexible w), а не зафиксировать w в одной точке.

---

## 9. ИЗМЕРЕНИЕ ЭМОЦИЙ В HBP

### 9.1. Батарея (дополнение к VII секции System Map)

| Уровень | Конструкт | Инструмент | Статус в HBP |
|---------|-----------|-----------|-------------|
| L0 | Интероцептивная осведомлённость | MAIA-2 (Body Listening, Self-Regulation) | Уже в батарее v1.4 |
| L0 | Интероцептивная точность | HDT (heartbeat discrimination task) | Уже в батарее v1.4; дебаты по валидности |
| L0 | Core affect dynamics | EMA: валентность + arousal (5× в день) | Уже в протоколе D-HBP |
| L2 | Эмоциональная гранулярность | EMA-derived ICC (intraclass correlation) | **НОВОЕ**: добавить в протокол |
| L2 | Эмоциональная регуляция | DERS-18 | Уже в батарее |
| Mood | Аффективная инерция/вариабельность | EMA time-series: autocorrelation, variance | **НОВОЕ**: добавить в CSD-pipeline |
| Bio | Vagal tone / CAN | HRV (RMSSD) | Уже в батарее |
| Bio | Симпатическая активация | EDA | Уже в батарее |
| L-HBP | Emotional language markers | LIWC negative emotion words (d=0.72) | Уже в L-HBP |

### 9.2. Новые APV-карты

**APV-E1: Эмоциональная гранулярность × CFR**
- Assumption: высокая эмоциональная гранулярность → высокий Flexibility (switching rate EMA)
- Prediction: r ≥ 0.30 между гранулярностью (ICC) и switching rate
- Validation: N = 120, EMA 14 дней, D-HBP pilot

**APV-E2: Precision re-weighting → эмоциональная гранулярность**
- Assumption: D-HBP Level 2 увеличивает эмоциональную гранулярность
- Prediction: pre-post increase in ICC ≥ 0.15 (Cohen's d ≥ 0.5)
- Validation: SCED + group comparison, D-HBP pilot

**APV-E3: Mood hyper-prior rigidity → depression**
- Assumption: аффективная инерция (autocorrelation EMA-valence) предсказывает PHQ-9
- Prediction: r ≥ 0.35 между 14-day autocorrelation и PHQ-9
- Validation: N = 120, baseline EMA

---

## 10. СИНТЕЗНАЯ ТАБЛИЦА: ТЕОРИИ × HBP-СОВМЕСТИМОСТЬ

| Теория | Ядерный тезис | Доказательность | HBP-совместимость | Интеграционный путь | Напряжение |
|--------|--------------|-----------------|-------------------|--------------------|-----------:|
| Barrett TCE | Эмоции конструируются как ad hoc категории | Высокая (meta-analyses) | Высокая (L2) | Концептуальный слой GM | Отрицает L1 |
| Panksepp/Solms | 7 врождённых аффективных систем | Средняя (animal + some human) | Высокая (L1) | Hardcoded priors | Экстраполяция с животных |
| Izard DET (revised) | Emotion schemas = эмоция+когниция | Средняя | Высокая | Emotion schema = аттрактор | Размытость basic/schema |
| Hesp et al. 2021 | Валентность = subjective fitness в deep AI | Теоретическая (simulations) | Очень высокая | Формальный backbone HEA | Нет эмпирики |
| Smith et al. 2019 | Эмоциональное осознание = иерархический inference | Теор. + partial empirical | Очень высокая | Алекситимия, awareness levels | — |
| Pattisapu et al. 2024 | Circumplex через FEP: arousal=entropy, valence=utility | Теоретическая (simulations) | Очень высокая | Операционализация L0 | Нет эмпирики |
| Colombetti | Primordial affectivity, enactive | Концептуальная | Высокая | Энактивное × реляционное | Слабая формализация |
| Moors 2022 | Goal-directed theory | Средняя-высокая | Высокая | 8 потребностей Рыжова × PE | — |
| Clark/Watson/Friston 2018 | Mood = hyper-prior | Теоретическая | Очень высокая | Mood × attractor trapping | Слабая эмпирика |
| Zavlis et al. 2025 | Формальная теория mood instability | Теор. + EMA data | Высокая | CFR × аффективная динамика | — |
| Greenberg EFT | Marker-guided emotion processing | Высокая (RCTs) | Высокая | D-HBP Level 2–3 | — |
| Damasio SMH | Соматические маркеры → решения | Ослабленная | Средняя | Subsumed by interoceptive inference | Слабая эмпирика |

---

## 11. НЕРЕШЁННЫЕ ВОПРОСЫ

1. **Barrett vs Panksepp на уровне L1**: Barrett (2025) настаивает на непримиримости. HBP-решение (иерархия) легитимно, но требует эмпирической верификации — задача для будущих исследований.
2. **Алекситимия: low precision on priors vs on PE?** Данные 2021 поддерживают attenuated prior precision; Smith et al. подчёркивают attentional allocation. Не взаимоисключающие — нужна дифференциальная диагностика.
3. **Mood как hyper-prior**: элегантно, но эмпирически слабо валидировано. APV-E3 — первый шаг.
4. **FM5 и FM6 эмоции**: наименее проработаны. Нужны отдельные исследования (цифровые эмоции, экологическая тревога).
5. **Кросс-культурная вариативность L2**: TCE предсказывает существенную вариативность → HBP должен учитывать это в ad hoc инструментах.

---

## 12. ПУБЛИКАЦИОННЫЙ ПОТЕНЦИАЛ

- **Tier 1**: *Neuroscience & Biobehavioral Reviews* (IF ~8) — «Hierarchical Emotion Architecture: Bridging Active Inference and Existential Psychotherapy»
- **Tier 2**: *Emotion* (APA, IF ~5) — «Emotion Granularity as a Marker of Therapeutic Change: An Active Inference Framework»
- **Tier 3**: *Frontiers in Psychology* (IF ~3) — «Precision Re-weighting in Emotion Regulation: From FEP to Clinical Practice»

---

## CHANGELOG
- v0.1 — 28.02.2026 — Initial draft. DR6 integration. HEA model (L0/L1/L2). 6 FM × emotion mapping. Precision dysregulation taxonomy. 3 APV cards. Synthesis table 12 theories.

---

## ИСТОЧНИКИ (КЛЮЧЕВЫЕ)
- Barrett et al. (2025). Basic Emotions or Constructed Emotions. PMC12065949
- Hesp et al. (2021). Deeply Felt Affect. Neural Computation, 33(2), 398–446
- Smith, Lane, Parr, Friston (2019). Neurocomputational model of emotional awareness. In Oxford Academic
- Pattisapu et al. (2024). Free Energy in a Circumplex Model of Emotion. arXiv:2407.02474
- Clark, Watson, Friston (2018). What is mood? A computational perspective. Psychological Medicine
- Izard (2009). Emotion theory and research: highlights. PMC2723854
- Solms (2021). The Hidden Spring. Norton
- Colombetti (2014). The Feeling Body. MIT Press
- Moors (2022). Goal-directed theory. In d-nb.info/1368220851/34
- Zavlis et al. (2025). A formal theory of mood instability. City Research Online
- Paulus et al. (2019/2023). Transdiagnostic failure to adapt interoceptive precision. PMC10593015
- Stephan et al. (2016). Allostatic self-efficacy. Frontiers in Human Neuroscience
- Widen & Russell (2008). Children acquire emotion categories gradually. Cognitive Development
- Cook (2025). Caregiver interoception. Essex PhD thesis
- Greenberg (2004/2015). Emotion-Focused Therapy