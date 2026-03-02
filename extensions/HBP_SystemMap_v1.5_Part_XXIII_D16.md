
========================================================================
ЧАСТЬ XXIII. ФОРМАЛЬНЫЕ МОСТЫ: IT / МАТЕМАТИКА / ФИЗИКА → HBP [v1.5, D16]
========================================================================

23.0. ПРЕАМБУЛА РАЗДЕЛА

Этот раздел систематизирует формальные соответствия (изоморфизмы,
гомоморфизмы) между концепциями IT, математики и физики — и конструктами
HBP. Источник: Deep Research 5 (27.02.2026), каталог из 33 трансферов.

Центральный тезис: FEP — вычислительный фреймворк. Поэтому IT-концепции —
не произвольные метафоры, а формальные аналоги. Пять ядерных понятий
(precision, free energy, аттрактор, CSD, network topology) связаны
единой математической тканью.

Принцип: изоморфизм > гомоморфизм > метафора. Метафоры допускаются
только для коммуникации (Ed-HBP, Pop-HBP), не для теоретизирования.
Антикаталог ложных аналогий — в секции 23.7.

Связь с ядром: П3 (двойное описание — формальный регистр),
П4 (FEP как конструал), П5 (active inference), П11 (сетевая динамика),
П12 (карта ≠ территория), П13 (PE как конструал).

------------------------------------------------------------------------
23.1. КАТАЛОГ: 33 ТРАНСФЕРА (СВОДНАЯ ТАБЛИЦА)
------------------------------------------------------------------------

Типы: ISO = изоморфизм (одна математика), HOM = гомоморфизм
(структурное подобие), META = метафора (только коммуникация).

 #  | Концепция                        | Тип  | HBP-привязка
----|----------------------------------|------|-------------------------------
 1  | Attractors / Phase Transitions   | ISO  | Патогенез (П4, П11, Часть IV)
 2  | Critical Slowing Down (CSD)      | ISO  | Предвестники (П11, Часть V)
 3  | Bayesian Inference / Pred. Coding | ISO  | FEP-ядро (П4, П5, П13)
 4  | Overfitting / Regularization     | ISO  | Software failure (Часть IV)
 5  | PID Control                      | ISO  | Active inference (П5, C-HBP)
 6  | Order Parameters / Slaving       | ISO  | Терапевтический процесс (П10)
 7  | Network Theory (Graph Theory)    | ISO  | Отношения Мясищева (П7, П11)
 8  | Exploration-Exploitation          | ISO  | Сужение бытия (П6, Часть V)
 9  | Compression / Rate-Distortion    | ISO  | Смыслообразование (П6 FM4)
10  | Renormalization / Criticality    | HOM  | C+F+R, SOC (Часть V)
11  | Catastrophic Forgetting / Sleep  | HOM  | Hardware failure, сон (П2)
12  | Shannon Channel Capacity         | HOM  | Когнитивные ограничения (П2)
13  | Category Theory                  | HOM  | Метаязык HBP (П3, П12)
14  | Model Predictive Control         | HOM  | Temporal depth, EFE (П5)
15  | Second-Order Cybernetics         | HOM  | Методология (П8, П12, Tier 0)
16  | Fluctuation Theorems             | HOM  | NESS, онтология (П1, Ч.XXII)
17  | VSM (Stafford Beer)              | HOM  | O-HBP
18  | Game Theory                      | HOM  | AISI, межличностные паттерны
19  | Lyapunov Exponents               | HOM  | Эмоциональная вариабельность
20  | Curriculum Learning              | HOM  | ЗБР Выготского, Ed-HBP
21  | Catastrophe Theory (cusp)        | HOM  | Типология переходов (Tier 2)
22  | Byzantine Fault Tolerance        | META | Эпистемическое доверие (П9)
23  | Mutual Information               | HOM  | Терапевтическая синхронность
24  | TCP Handshake                    | META | Rupture-repair (П8)
25  | Adaptive Control                 | HOM  | Аллостаз, мета-обучение
26  | Transfer Learning                | HOM  | Генерализация навыков
27  | CAP Theorem                      | META | Трейдоффы (коммуникация)
28  | ACID Transactions                | META | Антикаталог (23.7, A-3)
29  | Canary Deployment                | META | Градуальная экспозиция
30  | Eventual Consistency             | META | Антикаталог (23.7, A-4)
31  | Encryption / Firewall            | META | Антикаталог (23.7, A-1)
32  | Microservices vs Monolith        | META | Антикаталог (23.7, A-2)
33  | Consensus Algorithms             | META | Групповая динамика

Итого: 9 ISO, 17 HOM, 7 META.

------------------------------------------------------------------------
23.2. TIER 1: ПЯТЬ ЯДЕРНЫХ ИЗОМОРФИЗМОВ ДЛЯ НЕМЕДЛЕННОЙ ИНТЕГРАЦИИ
------------------------------------------------------------------------

23.2.1. PRECISION = REGULARIZATION → SOFTWARE FAILURE (T-4)

Формальный мост:
  F = accuracy − complexity.
  Precision-weighted PE: ε = π · (observation − prediction).
  π = 1/σ² = параметр регуляризации (идентично L2 penalty в ML).

Клинический спектр:
  Overfitting (π_sensory ↑↑): модель переподгоняется под каждый стимул.
    → Сенсорная перегрузка, ригидность, потеря генерализации.
    → Клинический аналог: ASD-like паттерны (Van de Cruys 2014, HIPPEA).
  Underfitting (π_prior ↑↑): модель навязывает предсказания, игнорируя данные.
    → Бред, галлюцинации, отрыв от реальности.
    → Клинический аналог: психотический спектр (Adams 2013).
  Balanced precision: оптимальная регуляризация = здоровый «софт».

Связь с этиологией HBP (Часть IV):
  Software failure = нарушение баланса precision.
  «Интериоризированный код» = priors + precision allocation.
  «Слишком жёсткий код» = overfitting.
  «Слишком рыхлый код» = underfitting.
  Терапия = precision re-weighting (Level 0–3, Часть VII).

Авторы: Lawson, Rees & Friston (2014); Van de Cruys et al. (2014);
Palmer et al. (2023, PLOS Comp Biol); Adams et al. (2013).

Added predictive value: единая ось precision balance предсказывает,
что ASD и психоз — противоположные полюса ОДНОГО параметра
(а не две независимые категории). Тестируемо через HGF
(learning rate, volatility estimation) в Части VII.

23.2.2. NETWORK THEORY → ФОРМАЛИЗАЦИЯ ОТНОШЕНИЙ МЯСИЩЕВА (T-7)

Формальный мост:
  Субъект = взвешенный граф G = (V, E, w).
  V = элементы системы (отношения, симптомы, мотивы).
  E = связи между элементами.
  w = strength of connection (= мера существенности связи К по Рыжову).

Три масштаба сетей (трёхуровневая модель):
  1. Внутрисубъектная: симптомы, аффекты, когниции как узлы.
     Инструмент: Borsboom network analysis, EMA → idiographic network.
  2. Межсубъектная: отношения субъекта (Мясищев).
     Hub-узлы = самые значимые отношения (П7).
     Bridge symptoms → коморбидность.
  3. Макросеть: социум, культура, цифровая среда (FM5, FM6).
     Scale-free properties на всех уровнях.

Связь с П7 (иерархия значимости):
  Значимость отношения = node centrality (betweenness / strength).
  Патогенез = удаление hub-узла → каскад (scale-free fragility).
  Мера существенности связи К (Рыжов, Часть XVII) = edge weight.

Связь с П11 (сетевая динамика):
  NCT controllability → мишени интервенции.
  Resilience = basin stability в ландшафте сети.
  CSD = network-level early warning.

Авторы: Borsboom (2017, World Psychiatry); McNally (2016);
Fried et al. (2017); Robinaugh et al. (2020).

Added predictive value: bridge centrality предсказывает коморбидность;
hub-removal предсказывает каскадную дезорганизацию → тестируемо
через EMA + network analysis в пилоте.

23.2.3. АТТРАКТОРЫ + CSD → ПАТОГЕНЕЗ И МОНИТОРИНГ (T-1, T-2)

Формальный мост:
  Аттрактор: множество состояний x* т.ч. lim_{t→∞} φ(t, x₀) = x*.
  Бифуркация: качественная смена топологии при изменении параметра μ.
  CSD: вблизи бифуркации λ_max → 0 → autocorrelation ↑, variance ↑.

Reference implementation (Schiepek 5-variable model):
  5 переменных: интенсивность эмоций (E), проблемность (P),
  мотивация (M), инсайт (I), успех (S).
  Связанные нелинейные разностные уравнения → хаос, бифуркации,
  мультистабильность (Schiepek et al. 2017, Frontiers in Psychology).

HBP-позиция:
  Каждое измерение бытия (П6) = проекция на подпространство
  многомерного аттрактора.
  Ригидный аттрактор = «locked-in brain» = патогенез (Часть IV).
  Терапия = целенаправленная дестабилизация через PE (П10).
  CSD = early warning, но с ограничениями:
    Sensitivity ~30–40% (Lövdén 2025, Helmich 2024).
    Статус: EXPLORATORY (не confirmatory).

Измерение:
  SNS (Synergetic Navigation System) — ежедневные опросники.
  EMA time series → autocorrelation, variance, dynamic complexity.
  Часть VII: CSD/SNS в вычислительном блоке батареи.

Авторы: Schiepek et al. (2017); van de Leemput et al. (2014, PNAS);
Helmich et al. (2023, 2024); Olthof et al. (2020); Kelso (2020).

Added predictive value: CSD предсказывает фазовый переход
ДО его наступления (а не ретроспективно). Тестируемо в пилоте
(APV Card H-5).

23.2.4. PID = ACTIVE INFERENCE → ОСНОВАНИЕ C-HBP (T-5)

Формальный мост (Baltieri & Buckley 2019, Entropy):
  Velocity form PID:
    u̇ = k_i · e + k_p · (de/dt) + k_d · (d²e/dt²)
  Active inference action:
    ȧ ≈ π_z(η − ψ) + π_z'(η' − ψ') + π_z''(η'' − ψ'')
  При ∂ψ/∂a = 1 → одно и то же уравнение.
  PID gains (k_p, k_i, k_d) = precisions (π_z, π_z', π_z'').

Клинический перевод:
  k_p (пропорциональный) = немедленная реакция на PE.
    ↑ π_z = повышенная чувствительность (тревожность).
    ↓ π_z = сниженная чувствительность (алекситимия).
  k_i (интегральный) = накопление хронического PE.
    Windup = хронический стресс: интегратор переполнен,
    но актуатор (coping) на пределе → burnout.
  k_d (дифференциальный) = чувствительность к СКОРОСТИ изменений.
    ↑ π_z'' = паника при быстрых изменениях.

Нейромодуляторная привязка:
  Дофамин → модулирует π на PE (= k_p).
  Серотонин → temporal discounting (= k_i tuning).
  Норадреналин → volatility estimation (= k_d).
  → Psychopharmacology = precision engineering.

Потенциал для C-HBP: мост между фармакологией и precision re-weighting.
Performance-robustness tradeoff = баланс чувствительности / стабильности.

Авторы: Baltieri & Buckley (2019); Sennesh et al. (2021);
Howlett & Paulus (2024).

Added predictive value: PID windup предсказывает, что хронический
стресс с ограниченным coping → качественно отличается от острого
стресса (не просто «больше», а другой режим). Тестируемо через
HPA-динамику (кортизол CAR, Часть VII).

23.2.5. EXPLORATION-EXPLOITATION → «СУЖЕНИЕ БЫТИЯ» (T-8)

Формальный мост:
  Expected free energy: G(π) = ambiguity + risk.
  Epistemic value (exploration) vs pragmatic value (exploitation).
  Temperature parameter β модулирует баланс.
  Дофамин → exploration bonus (Daw et al. 2006).

Клинический перевод:
  Депрессия = collapsed exploration (β → ∞, exploitation-only mode).
    Пространство возможных действий сужается.
    «Сужение бытия» (HBP) = ↓ exploration across all dimensions.
  Мания = excessive exploration (β → 0, random sampling).
  Апатия = ↓ expected value across ALL options → neither explore nor exploit.
  Ангедония ≠ апатия: ангедония = ↓ reward signal; апатия = ↓ action initiation.

Операционализация:
  Bandit-задачи (restless 2-armed bandit, Daw et al. 2006)
  → параметры: learning rate (α), exploration bonus (ε), temperature (β).
  = вычислительные биомаркеры для батареи Level C (Часть VII).

Связь с П6 (6 измерений):
  Exploration по каждому измерению — диагностически информативно:
    FM1: exploration в физическом мире (активность, движение)
    FM2: exploration в отношениях (новые связи, близость)
    FM3: exploration самости (новые роли, идентичность)
    FM4: exploration смысла (новые проекты, ценности)
    FM5: exploration в цифровом (новые платформы, AI)
    FM6: exploration в конечности (отношение к смерти, экзистенциальные вопросы)

Авторы: Addicott et al. (2017, Neuropsychopharmacology);
Daw et al. (2006); Friston (2017); Danwitz & von Helversen (2025).

Added predictive value: exploration bonus ε при депрессии
предсказывает скорость ответа на behavioral activation
→ тестируемо через bandit-task pre/post.

------------------------------------------------------------------------
23.3. TIER 2: ГОМОМОРФИЗМЫ ДЛЯ АДАПТИРОВАННОЙ ИНТЕГРАЦИИ
------------------------------------------------------------------------

23.3.1. Synergetics (Haken) → Теория процесса терапии (T-6)
  Параметры порядка = ключевые переменные (E, P, M, I, S в модели Schiepek).
  Slaving principle: 1–2 параметра порядка подчиняют остальные.
  HBP: ключевое отношение (П7) = параметр порядка.
  SNS → инструмент для B-HBP процесс-мониторинга.
  Circular causality: параметр порядка одновременно порождается
  подсистемами и управляет ими ≈ П1 (бытие как процесс).

23.3.2. Compression / Rate-Distortion → Смыслообразование (T-9/T-11)
  R(D) = min I(X; X̂) при E[d(X, X̂)] ≤ D.
  Hub-регионы мозга = lossy compressors (Zhou et al. 2022).
  Compression efficiency предсказывает executive function, memory,
  reasoning, social cognition.
  HBP: «смысл» (FM4) = lossy compression потока бытия.
  Нарратив = compressed representation аттракторной истории.

23.3.3. Channel Capacity → Когнитивные ограничения (T-11)
  Cognitive control capacity ≈ 3–4 bit/s (Nature 2016).
  = фундаментальный bottleneck бытия-в-мире.
  Бытие-в-цифре (FM5): digital overload = channel capacity exceeded.

23.3.4. Category Theory → Метаязык (T-12)
  Functor = representation. Natural transformation = analogy.
  ВСЕ изоморфизмы в этом разделе = functors между категориями.
  Потенциал: строгая проверка непротиворечивости между секциями
  System Map через natural transformations.
  Статус: TRL 1 (теоретический, без клинической операционализации).

23.3.5. Catastrophic Forgetting / Sleep → Hardware failure (T-10)
  Сон = offline replay для предотвращения catastrophic forgetting.
  Геометрия: sleep → intersection of weight manifolds (Gonzalez 2022).
  HBP: нарушение сна → деградация ВСЕХ измерений бытия (каскад).
  Reconsolidation window (П10) = controlled replay.
  EMDR / сновидческая работа = управляемый replay.

23.3.6. MPC / Planning → Temporal Depth (T-13)
  G(π) = Σ_τ [ambiguity + risk]. При τ → 1: рефлексивный контроль.
  При τ → N: goal-directed planning.
  Депрессия = collapsed temporal depth → «не вижу будущего».
  FM6 (бытие-в-конечности) = максимальный temporal depth.

23.3.7. Fluctuation Theorems → Онтология бытия (T-15)
  Уже интегрировано в Часть XXII (NESS, dissipative structures).
  Перекрёстная ссылка: 22.1–22.2.

------------------------------------------------------------------------
23.4. НЕОЖИДАННЫЕ НАХОДКИ
------------------------------------------------------------------------

N-1. Compression efficiency в коннектоме (Zhou et al. 2022):
  Hub-регионы мозга = «ZIP-архиваторы» — не метафора, а формализуемое
  утверждение через rate-distortion theory. Предсказывает поведение
  лучше, чем стандартная network efficiency.

N-2. Adjoint Functors → Dual-Process Cognition (Phillips 2016):
  System 1 / System 2 формализуется через adjoint functors
  в теории категорий. HBP: переключение между режимами «софта».

N-3. Sleep = Intersection of Weight Manifolds (Gonzalez 2022):
  Сон — не «отдых», а поиск точки в многомерном пространстве,
  где совместимы все выученные паттерны. Геометрическая интерпретация.

N-4. PID Gains = Precisions = Нейромодуляторы (Baltieri 2019):
  k_p, k_i, k_d → π_z, π_z', π_z'' → дофамин, серотонин, норадреналин.
  Psychopharmacology = precision engineering = PID tuning.

N-5. Canary Deployment ↔ Градуальная экспозиция:
  Метафора без формального моста, но процедурно изоморфна:
  deploy 1–5% → monitor → expand → rollback if needed.
  Полезна для Ed-HBP / Pop-HBP.

------------------------------------------------------------------------
23.5. МЕТОД REVERSE IT HEURISTIC (RIH)
------------------------------------------------------------------------

Формализация эвристического метода, использованного для генерации
каталога. Может быть использован для будущих расширений.

Алгоритм:
  1. Взять зрелую IT/Math/Physics-концепцию с чёткой математикой.
  2. Проверить: существует ли формальный изоморфизм (одна математика)
     или гомоморфизм (структурное подобие с потерями)?
  3. Если да → сформулировать тестируемую гипотезу для HBP.
  4. Применить двойной фильтр (Часть III):
     Критерий 1: FEP-переводимость.
     Критерий 2: Операциональный маркер.
  5. Проверить added predictive value.
  6. Если проходит все фильтры → Tier 1/2; если нет → Tier 3 или META.

Обоснование: FEP сам по себе — вычислительный фреймворк (variational
Bayes + dynamical systems + information theory). IT-концепции —
не произвольные аналогии, а родственные формализмы из той же
математической семьи.

Ограничение: RIH генерирует гипотезы, не доказательства.
Каждая гипотеза требует эмпирической проверки (П12).

------------------------------------------------------------------------
23.6. ТРЁХУРОВНЕВАЯ СЕТЕВАЯ МОДЕЛЬ БЫТИЯ
------------------------------------------------------------------------

Обобщение T-7 (Network Theory) на все масштабы HBP:

УРОВЕНЬ 1 — ВНУТРИСУБЪЕКТНАЯ СЕТЬ (intra-individual):
  Узлы: симптомы, аффекты, когниции, телесные состояния.
  Рёбра: причинные связи (EMA → temporal network).
  Инструменты: Borsboom network analysis, nctpy (NCT).
  HBP-привязка: П11, Часть IV (патогенез).

УРОВЕНЬ 2 — МЕЖСУБЪЕКТНАЯ СЕТЬ (inter-individual):
  Узлы: субъекты (клиент, терапевт, значимые другие).
  Рёбра: отношения (= система отношений Мясищева, П7).
  AISI (П8) = belief synchronization между узлами.
  Инструменты: WAI-SR, ECR-12, social network analysis.
  HBP-привязка: П7, П8, П9.

УРОВЕНЬ 3 — МАКРОСЕТЬ (macro-social):
  Узлы: социальные группы, институты, цифровые платформы.
  Рёбра: культурные нормы, алгоритмические связи, экономические потоки.
  Scale-free properties на этом уровне → hub-институты.
  HBP-привязка: П6 FM5 (Digitalwelt), FM6 (Endlichkeit).

Единая математика: теория графов, centrality, bridges, Ising model —
применима на ВСЕХ трёх уровнях. Различаются единицы анализа
и масштаб, не формализм.

------------------------------------------------------------------------
23.7. АНТИКАТАЛОГ: ЛОЖНЫЕ АНАЛОГИИ (НЕ ИНТЕГРИРОВАТЬ)
------------------------------------------------------------------------

A-1. Encryption / Firewall → Защитные механизмы.
  Нет общей математики. Firewall работает по правилам (ACL);
  защиты — бессознательны. Encryption сохраняет информацию;
  вытеснение уничтожает доступ. Вердикт: только для психообразования.

A-2. Microservices vs Monolith → Модулярный разум (Fodor).
  Microservices — архитектурный выбор; модулярность — свойство биологии.
  Massive modularity (Carruthers) vs Fodor — открытый спор.
  Нет единой математической модели. Вердикт: limited utility.

A-3. ACID Transactions → Целостность психологических изменений.
  В психологии: нет rollback, partial change — норма,
  isolation невозможна, durability — именно то, что не работает
  (рецидив). Вердикт: красивая метафора, бесполезна как инструмент.

A-4. Eventual Consistency → Когнитивный диссонанс.
  Convergence в BASE гарантирована алгоритмически;
  человек может жить с противоречиями всю жизнь.
  Нет общей математической структуры. Вердикт: слабая аналогия.

A-5. Quantum Mechanics → Сознание.
  Penrose-Hameroff: за пределами нашей эпистемологии (П12).
  Нет воспроизводимых данных о квантовых эффектах на масштабах,
  релевантных для когниции. Вердикт: ИСКЛЮЧЕНО.

------------------------------------------------------------------------
23.8. ПРОВЕРКА НЕПРОТИВОРЕЧИВОСТИ С ЯДРОМ
------------------------------------------------------------------------

| Постулат | OK | Комментарий                                    |
|----------|----|------------------------------------------------|
| П1       | ✅ | Бытие = multi-scale network (23.6)             |
| П2       | ✅ | Субстрат = hardware (PID gains, sleep replay)  |
| П3       | ✅ | Формальный регистр = весь раздел               |
| П4       | ✅ | FEP = конструал, ISO-мосты — его развитие      |
| П5       | ✅ | Active inference = PID (23.2.4)                |
| П6       | ✅ | 6 FM = exploration dimensions (23.2.5)         |
| П7       | ✅ | Значимость = centrality (23.2.2)               |
| П8       | ✅ | AISI = Level 2 network (23.6)                  |
| П9       | ✅ | ET = Byzantine tolerance (META, не ISO)        |
| П10      | ✅ | Mismatch = phase transition trigger (23.2.3)   |
| П11      | ✅ | Сетевая динамика = core T-7 (23.2.2)          |
| П12      | ✅ | Антикаталог (23.7) = дисциплина мышления       |
| П13      | ✅ | PE = universal (T-3, T-4)                      |
| П14      | ✅ | Level A/B/C → Tier 1/2/3 мостов              |

Непротиворечивость: 14/14 постулатов ✅.

------------------------------------------------------------------------
23.9. ПУБЛИКАЦИОННЫЙ ПОТЕНЦИАЛ
------------------------------------------------------------------------

Целевой формат: обзорная статья «Formal Bridges Between Computational
Science and Clinical Psychology: A Systematic Catalog»
Целевые журналы:
  - Neuroscience & Biobehavioral Reviews (IF ~8)
  - Physics of Life Reviews (IF ~11)
  - Frontiers in Psychology — Theoretical (IF ~3)
TRL: 2–3 (conceptual catalog + partial evidence).

------------------------------------------------------------------------
23.10. CHANGELOG РАЗДЕЛА
------------------------------------------------------------------------

v1.0 (28.02.2026):
- Полный раздел создан
- Источник: DR5-transfer.md, dr5_catalog.csv
- 33 трансфера, 5 Tier 1, 7 Tier 2, 5 неожиданных находок
- RIH метод формализован
- Трёхуровневая сетевая модель
- Антикаталог: 5 ложных аналогий
- Непротиворечивость: 14/14 ✅
