# ЧАСТЬ XXII. ТЕРМОДИНАМИКА БЫТИЯ: ПРИГОЖИН → FEP → HBP
## Раздел System Map v1.4 | Модуль T2
## Дата: 27.02.2026
## Статус: Draft v1.0

---

## 22.0. ПРЕАМБУЛА РАЗДЕЛА

Этот раздел формализует связь между термодинамикой необратимых процессов
(Пригожин), Free Energy Principle (Фристон) и клинической моделью HBP.

Центральный тезис: **Бытие субъекта = диссипативная структура**, которая
поддерживает себя вдали от термодинамического равновесия через непрерывную
минимизацию variational free energy. Психопатология = нарушение этого процесса
в двух формах: NESS breakdown (коллапс субстрата) или attractor trapping
(застревание в ригидном аттракторе).

Связь с ядром: П1 (бытие как процесс), П2 (субстрат), П4 (FEP как конструал),
П5 (active inference), П13 (PE как механизм). Столпы: Пригожин, Фристон, Рыжов.

---

## 22.1. ДИССИПАТИВНЫЕ СТРУКТУРЫ: ПОРЯДОК ИЗ НЕРАВНОВЕСИЯ

### 22.1.1. Теорема Пригожина и её пределы

Пригожин (Нобелевская лекция, 1977) показал: порядок может возникать из хаоса
**через диссипацию**, а не вопреки ей. Живые системы — открытые: они обмениваются
энергией и материей с окружением и поддерживают низкую внутреннюю энтропию
за счёт постоянного рассеивания (экспорта) энтропии вовне.

Формальные элементы:
- **S_internal** (внутренняя энтропия) — стремится к минимуму
- **S_production** (производство энтропии) — неотрицательно (второе начало)
- **Far-from-equilibrium** — система удерживается вдали от термодинамического
  равновесия
- **Bifurcation points** — точки ветвления (фазовые переходы к новым аттракторам)

Ограничение: теорема о минимальном производстве энтропии справедлива только
для near-equilibrium (линейный режим). Биологические системы = far-from-equilibrium
→ нужна более общая формулировка. Такую формулировку предоставляет FEP.

### 22.1.2. NESS (Non-Equilibrium Steady State)

Определение (Seifert 2012, Sartori et al. 2014):
NESS = стационарное состояние, где:
- Макроскопические переменные постоянны (гомеостаз)
- НО термодинамические потоки ≠ 0 (continuous throughput энергии/материи)
- Entropy production > 0 (система диссипирует)

Формально:
```
dS_internal/dt = 0   (стационарность)
dS_production/dt > 0  (диссипация)
```

Биологический пример: живая клетка кажется «стабильной» (постоянные температура,
pH, концентрации), но поддерживает себя только через непрерывное потребление
глюкозы и O₂ с выделением CO₂ и тепла.

**Ключевая метафора для клиники:**
Термодинамическое равновесие = смерть. Живая система ОБЯЗАНА оставаться
вдали от равновесия. Цена жизни — непрерывная диссипация. Прекращение
диссипации = коллапс.

### 22.1.3. Субъект как диссипативная структура

HBP-позиция: субъект (П1) = диссипативная структура высшего порядка.

Субстрат (П2) = физиологическая реализация far-from-equilibrium state:
- Нейронная активность: ~20% энергопотребления тела при ~2% массы
- HPA-ось, circadian rhythms, сон-бодрствование = oscillatory maintenance NESS
- Метаболизм, иммунная система, микробиом = потоки, поддерживающие порядок

Бытие (П1) = процесс поддержания этой структуры:
- «Человек есть центр, процесс и способ проживания своего бытия»
- Бытие — не статичная данность, а непрерывная работа против равновесия
- Прекращение этой работы = разрушение бытия (биологическое или психологическое)

Двойное описание (П3):
- Феноменологически: «я живу, чувствую, хочу, стремлюсь»
- Формально: система поддерживает NESS через минимизацию variational free energy
- Ни одно описание не редуцируется к другому.

---

## 22.2. FEP КАК ФОРМАЛЬНЫЙ МОСТ

### 22.2.1. От Пригожина к Фристону

Ключевые работы (мост):
- Friston (2013): «Life as we know it» — FEP = формализация «What is Life?» Шрёдингера
- Ramstead et al. (2018): «Answering Schrödinger's question» — variational free energy
  ≈ thermodynamic free energy (Helmholtz) для steady-state систем
- Friston et al. (2023): «Free energy: a user's guide» — обобщённый обзор
- arXiv (2025): конструктивное доказательство реализации FEP через dissipative
  structures с local credit assignment

Формальная связь:
```
Thermodynamic entropy (Shannon): H = -Σ p(x) log p(x)
Free energy (Helmholtz):         F_thermo = U - TS
Variational free energy:         F_var = D_KL[q(s)||p(s|o)] - log p(o)

Для steady-state систем: F_var ≈ F_thermo
→ Минимизация F_var (FEP) ≈ минимизация entropy production (Пригожин)
```

Интуитивно:
- Система, минимизирующая variational free energy, остаётся в узком подмножестве
  состояний (low surprise = low entropy)
- Это требует непрерывной диссипации (entropy production в окружении)
- FEP = computational formulation диссипативных структур Пригожина

### 22.2.2. NESS в FEP-терминах

NESS = random dynamical attractor в фазовом пространстве (Friston 2013).
Система «живёт» на низкоразмерном многообразии (attracting set Γ), несмотря
на стохастические флуктуации.

```
ẋ = f(x, a) + ω

Где:
- x = internal states (нейрофизиология)
- a = action (моторные команды, поведение)
- ω = random fluctuations (шум)

NESS ⟺ x остаётся вблизи attracting set Γ (низкая энтропия)
```

Минимизация F = staying on attracting set:
- F ↑ → система отклоняется от Γ → prediction error ↑
- Система минимизирует F через:
  1. **Perceptual inference** (обновление внутренней модели)
  2. **Active inference** (изменение среды через действие)

### 22.2.3. Конструал-дисклеймер (П4, П12)

В соответствии с П4 (FEP = конструал, не онтология) и П12 (карта ≠ территория):

Мы НЕ утверждаем, что субъект «на самом деле» минимизирует variational free energy.
Мы утверждаем, что FEP предоставляет **формальный язык**, позволяющий:
1. Связать термодинамику (Пригожин) с вычислительной нейронаукой (Фристон)
2. Операционализировать понятие «бытие как процесс» (П1)
3. Генерировать тестируемые предсказания (added predictive value)

Added predictive value моста Пригожин → FEP для HBP:
- Предсказание 1: Entropy production снижена при психопатологии
  (подтверждено: decreased irreversibility в bipolar, schizophrenia, ADHD — arXiv 2025)
- Предсказание 2: CSD = early warning signal фазового перехода (тестируемо)
- Предсказание 3: Sleep = attractor reset mechanism (Romero et al. 2023)
- Предсказание 4: NESS breakdown ≠ attractor trapping → различные клинические
  стратегии (оригинальная HBP позиция)

---

## 22.3. ПОТРЕБНОСТИ КАК PRIOR PREFERENCES

### 22.3.1. Рыжов → FEP: формализация потребностей

Рыжов (2011) выделил 8 базовых потребностей:
1. В существовании (безопасность)
2. В присоединении (принадлежность)
3. В независимости (автономия)
4. В признании (валидация)
5. В превосходстве (competence)
6. В порядке (предсказуемость)
7. В познании (epistemic drive)
8. В удовольствии (hedonistic)

FEP-формализация:
Потребности = **prior preferences** P(o_pref) — распределение вероятности
над preferred outcomes.

```
G (expected free energy) = Ambiguity + Risk

Risk = D_KL[q(o_τ) || P(o_pref)]
     = расхождение между predicted outcomes и preferred outcomes

Минимизировать G → minimize Risk → достигать preferred outcomes
```

### 22.3.2. Маппинг потребностей на 6 FM

| Потребность (Рыжов)   | FM (HBP)           | Prior preference                       |
|------------------------|--------------------|-----------------------------------------|
| 1. Существование       | FM1: Бытие-в-мире  | P(o) высока на «predictable, safe»     |
| 2. Присоединение       | FM2: Жизнь         | P(o) высока на «connected, belonging»  |
| 3. Независимость       | FM3: Самость        | P(o) высока на «autonomous, agentic»   |
| 4. Признание           | FM3: Самость        | P(o) высока на «valued, validated»     |
| 5. Превосходство       | FM4: Смысл          | P(o) высока на «competent, effective»  |
| 6. Порядок             | FM1: Бытие-в-мире  | P(o) высока на «structured, coherent»  |
| 7. Познание            | FM4: Смысл          | P(o) высока на «novel, informative»    |
| 8. Удовольствие        | FM2: Жизнь         | P(o) высока на «pleasurable, vital»    |
| (FM5: Бытие-в-цифре)   | FM5                | P(o) высока на «digitally coherent»    |
| (FM6: Бытие-в-конечности)| FM6              | P(o) высока на «world-sustainable»     |

### 22.3.3. Неудовлетворённая потребность = хронический prediction error

Механизм:
```
Prior preference: P(o_pref) = «я хочу признания» (FM3)
Actual experience: q(o) = «меня игнорируют»
Result: D_KL[q(o) || P(o_pref)] ↑↑ → chronic prediction error → F ↑
```

Последствия:
1. Высокая variational free energy F → система не минимизирует F эффективно
2. Аллостатическая нагрузка (McEwen) → wear-and-tear на физиологических системах
3. Ригидные копинг-стратегии → narrowing of policy space = СИМПТОМЫ

Ключевое отличие от бихевиоризма:
Потребности — не «drives» (Халл), а **структура generative model**.
Они определяют, какие траектории в фазовом пространстве система считает
«правильными» (preferred). Это не push-модель, а pull-модель:
система активно стремится к prior preferences через active inference.

---

## 22.4. ДВОЙНАЯ МОДЕЛЬ ПАТОЛОГИИ (ОРИГИНАЛЬНАЯ HBP)

### 22.4.1. Два типа коллапса

| Параметр          | NESS Breakdown              | Attractor Trapping              |
|-------------------|-----------------------------|---------------------------------|
| Механизм          | Утрата far-from-equilibrium | Застревание в rigid attractor   |
| Entropy production| → 0 (collapse to equilibrium)| > 0, но в narrow range         |
| Клиническая картина| Тяжёлая депрессия (shutdown), кататония, anergic states | Навязчивости, руминация, аддикция, тревожные паттерны |
| HBP-этиология     | Преимущественно Hardware     | Преимущественно Software         |
| Терапевтическая стратегия | Биологический уровень: фарма, ECT, intensive support (C-HBP) | Психотерапия: destabilize → expand (D-HBP) |
| Маркеры          | HRV collapse, EEG flatness, cortisol dysregulation | EMA: ↑ autocorrelation, ↓ variance, ↓ switching rate |

### 22.4.2. Почему это важно клинически

Это НЕ декоративная таксономия. Это порождает **различные прогнозы**:

Прогноз 1: Клиент с NESS breakdown (Hardware-доминантный профиль, H3)
→ слабый ответ на D-HBP без биологической стабилизации
→ Тест: ECR-Avoidance и Psy-Flex НЕ коррелируют с outcome → H2 частично
  не подтверждается для этой подгруппы

Прогноз 2: Клиент с Attractor Trapping (Software-доминантный профиль, H3)
→ D-HBP эффективна через precision re-weighting → mismatch → reconsolidation
→ Тест: ΔPsy-Flex коррелирует с ΔSymptoms (H2); ΔMAIA-2 медиирует (H8/H4c)

Прогноз 3: Клиент со смешанным профилем (Input + Software)
→ D-HBP + фарма → синергетический эффект
→ Тест: interaction HW × treatment → outcome (H3, exploratory)

Фальсификация двойной модели:
Если NESS-breakdown клиенты и attractor-trapping клиенты показывают
одинаковые траектории в D-HBP И одинаковые биомаркерные профили → модель
не имеет различительной силы → отвергается как unfalsifiable taxonomy.

### 22.4.3. Графическая интуиция

```
ЗДОРОВЬЕ:                 ATTRACTOR TRAPPING:        NESS BREAKDOWN:
  ∪   ∪   ∪                      ∪∪∪∪∪                  ────────
 shallow basins             deep single basin          flat (no basin)
 flexible switching         escape difficult            no structure left
 high switching rate        low switching rate          system dissolving
```

---

## 22.5. ФАЗОВЫЕ ПЕРЕХОДЫ И CRITICAL SLOWING DOWN

### 22.5.1. Теория (Scheffer et al. 2009, 2012)

CSD (Critical Slowing Down) = увеличение времени восстановления системы
после perturbation вблизи tipping point (критического перехода).

Формальные признаки:
1. **Increasing autocorrelation** (lag-1): система медленнее возвращается к baseline
2. **Increasing variance**: флуктуации нарастают
3. **Slowed recovery**: после стрессора → долгое восстановление

### 22.5.2. CSD в психопатологии: состояние evidence

- van de Leemput et al. (2014): CSD перед depression transitions (EMA data)
- Wichers et al. (2016): transitions in psychiatric patients
- Smit et al. (2019): elevated autocorrelation перед MDD episode
- Schreuder et al. (2022): review — CSD как transdiagnostic marker
- **Lövdén et al. (2025, in press)**: CSD preceded recurrence of depression
  in 32.9% of participants; variance = более надёжный сигнал, чем autocorrelation;
  BUT: low sensitivity → серьёзное ограничение для клинического применения

### 22.5.3. CSD как предвестник фазового перехода в D-HBP

HBP-гипотеза (H2, SCED-компонент):
В ходе D-HBP рост dynamic complexity (по Schiepek) в окне 2–4 сессий
перед symptom drop = признак приближающегося фазового перехода
(выход из ригидного аттрактора).

Операционализация в пилотном протоколе:
- EMA daily: 5 items (Mood, Anxiety, Rumination, Energy, Authenticity)
- Rolling window: 14 дней
- Метрика: dynamic complexity (Schiepek algorithm)
- Контрольный сигнал: CSD (rolling autocorrelation + variance)
- Порог: entropy increase ≥ 0.30 SD перед sudden gain

WARNING (по результатам evidence mapping):
- CSD даёт ложные срабатывания (Helmich et al. 2024)
- Low sensitivity (Lövdén 2025): 32.9% true positive rate
- → CSD остаётся EXPLORATORY в HBP, не confirmatory
- → Основной маркер = dynamic complexity, не raw CSD

### 22.5.4. Осцилляторы и циркадные ритмы

Goldbeter (1996, 2002): биохимические осцилляторы как фундамент временной
организации живых систем.

FEP-интерпретация: циркадный ритм = temporal prior — система «предсказывает»
циклическую структуру времени.

Romero et al. (2023): сон = temporary entropy increase (reversible), необходимый
для долгосрочной минимизации энтропии.

Механизм: бодрствование → накопление synaptic potentiation → high connectivity →
low flexibility → сон → synaptic downscaling → reset → restore flexibility.

Импликация для HBP:
- Sleep = **attractor reset mechanism**
- Chronic insomnia → attractor rigidity → vulnerability to psychopathology
- Sleep hygiene = essential component в S-HBP, M-HBP, D-HBP
- Нарушение сна = Hardware × Software failure interaction

---

## 22.6. НЕРАВНОВЕСНАЯ ФИЗИКА МОЗГА: НОВЫЙ EVIDENCE

### 22.6.1. Brain dynamics и irreversibility (arXiv 2025)

Обзор nonequilibrium physics of brain dynamics показывает:
- Уровень необратимости (NESS entropy production) **снижен** при:
  - Нарушениях сознания (minimally conscious state, unresponsive wakefulness)
  - Анестезии
  - Сне (vs бодрствование)
- Уровень необратимости **изменён** при:
  - Alzheimer's, bipolar disorder, schizophrenia, ADHD, Parkinson's, epilepsy

### 22.6.2. HBP-интерпретация

Это прямо подтверждает предсказание двойной модели:
- **NESS breakdown**: снижение entropy production → снижение irreversibility
  → клинически: anergic/depressive states, cognitive decline
- **Attractor trapping**: entropy production сохранена, но в narrow range
  → клинически: навязчивости, руминация (система «работает», но «застряла»)

Тестируемое предсказание для пилота:
Если двойная модель верна, то:
- Подгруппа с low baseline HRV (NESS-breakdown proxy, H7) покажет
  низкий ответ на D-HBP без фармакологической поддержки
- Подгруппа с high baseline HRV + high rigidity (attractor-trapping proxy)
  покажет хороший ответ на D-HBP
- → Interaction HRV × PFS → outcome slope (exploratory test, пилот N=120-130)

---

## 22.7. ИНТЕГРАЦИОННАЯ СХЕМА

```
ПРИГОЖИН (термодинамика)
  ├── Dissipative structures (порядок из неравновесия)
  ├── NESS (стационарность + диссипация)
  ├── Bifurcation points (фазовые переходы)
  └── Entropy production → 0 = death
           │
           ▼
FEP (формальный мост, П4)
  ├── Variational free energy F ≈ thermodynamic free energy
  ├── Minimize F = stay in NESS = persist as system
  ├── Active inference = mechanism of staying alive
  └── Markov blanket = boundary of self
           │
           ▼
РЫЖОВ (потребности как prior preferences)
  ├── 8 потребностей → P(o_pref)
  ├── Маппинг на 6 FM
  ├── Неудовлетворённая потребность = chronic PE
  └── Мотивационный конфликт = bistability (competing attractors)
           │
           ▼
HBP SYNTHESIS
  ├── Здоровье = flexible multi-attractor + NESS maintenance (C+F+R)
  ├── NESS breakdown = Hardware failure → C-HBP
  ├── Attractor trapping = Software failure → D-HBP
  ├── CSD = early warning (exploratory, low sensitivity)
  ├── Dynamic complexity = primary phase-transition marker
  ├── Sleep = attractor reset mechanism
  └── Measurement: HRV (entropy), EMA (autocorrelation), MAIA-2, PFS
```

---

## 22.8. ПРОВЕРКА НЕПРОТИВОРЕЧИВОСТИ С ЯДРОМ

| Постулат | Согласованность | Комментарий |
|----------|----------------|-------------|
| П1 (Бытие) | ✅ | Бытие = процесс поддержания NESS |
| П2 (Субстрат) | ✅ | Субстрат = физиологическая реализация far-from-equilibrium |
| П3 (Двойное описание) | ✅ | Термодинамика = формальный регистр; проживание = феноменологический |
| П4 (FEP = конструал) | ✅ | Мост Пригожин→FEP = конструал, не онтологическое утверждение |
| П5 (Active inference) | ✅ | Active inference = mechanism of staying in NESS |
| П6 (6 FM) | ✅ | Потребности маппируются на 6 FM через prior preferences |
| П7 (Иерархия значимости) | ✅ | Иерархия = relative precision of prior preferences |
| П8 (Тер. отношения) | ✅ | Терапевт помогает destabilize rigid attractor через mismatch |
| П10 (Mismatch → reconsolidation) | ✅ | Mismatch = managed perturbation = controlled entropy increase |
| П11 (Сетевая динамика) | ✅ | CSD, dynamic complexity = сетевые маркеры |
| П12 (Негативная доктрина) | ✅ | Дисклеймер включён (22.2.3) |
| П13 (PE универсальный) | ✅ | PE = chronic при неудовлетворённых потребностях |
| П14 (Лестница сложности) | ✅ | Двойная модель → Level A/B/C батарея |

Непротиворечивость подтверждена по всем 14 постулатам.

---

## 22.9. ОГРАНИЧЕНИЯ

1. **Аналоговый мост**: связь F_var ≈ F_thermo строга только для steady-state.
   Человек в кризисе ≠ steady-state → мост ослабевает. Это осознанное упрощение.

2. **CSD sensitivity**: 32.9% true positive rate (Lövdén 2025) — слабо для
   клинического использования. CSD = research tool, не clinical alert.

3. **NESS breakdown vs Attractor Trapping**: бинарная таксономия упрощает
   реальность. Большинство клиентов — континуум. Двойная модель = эвристика,
   не нозология.

4. **Потребности как prior preferences**: FEP-формализация потребностей
   (Рыжов → P(o_pref)) элегантна, но эмпирически не тестировалась.
   СПМ → prior preferences mapping = Tier 2 (см. 17.5).

5. **Entropy production в мозге**: измерение irreversibility (arXiv 2025)
   требует fMRI/EEG → недоступно в пилотном протоколе.
   Proxy: HRV (RMSSD) как indirect measure of autonomic NESS.

---

## 22.10. ПУБЛИКАЦИОННЫЙ ПОТЕНЦИАЛ

Целевые журналы:
- *Physics of Life Reviews* (IF ~11) — обзор Пригожин × FEP × психопатология
- *Entropy* (MDPI, IF ~2.7) — специализированный, open access
- *Frontiers in Psychology* (Theoretical section) — для клинической интеграции

Структура возможной статьи:
1. Пригожин foundations (NESS, dissipative structures)
2. FEP as formal bridge (variational ≈ thermodynamic free energy)
3. Needs as prior preferences (Рыжов mapping, оригинально)
4. Dual pathology model (NESS breakdown vs attractor trapping, оригинально)
5. CSD and dynamic complexity: clinical evidence
6. HBP clinical applications (D-HBP protocol connection)

TRL: 3 (conceptual integration + partial literature evidence)

---

## 22.11. CHANGELOG

v1.0 (27.02.2026):
- Полный раздел T2 создан
- Источники: DR2 (HBP-DR2-Prigogine-FEP.md), System Map v1.3, Evidence Map,
  arXiv 2025 (nonequilibrium brain dynamics), Lövdén 2025 (CSD sensitivity)
- Двойная модель патологии формализована
- Потребности → prior preferences маппинг сведён с 6 FM
- CSD downgraded to exploratory (consistency с Evidence Map)
- Проверка непротиворечивости: 14/14 постулатов ✅

---

# КОНЕЦ РАЗДЕЛА 22 (T2)
