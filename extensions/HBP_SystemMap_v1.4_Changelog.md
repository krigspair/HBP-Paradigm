# HBP SYSTEM MAP — CHANGELOG v1.3 → v1.4
# Дата: 27.02.2026
# Модуль: И-2 (Интеграция)
# Статус: Draft

---

# ОБЗОР ИЗМЕНЕНИЙ

| Параметр               | v1.3                        | v1.4                                |
|-------------------------|-----------------------------|-------------------------------------|
| Объём                   | ~58 000 символов (44 500 PDF)| ~77 500 символов (est.)            |
| Частей                  | XXI (1–XXI)                 | XXII (1–XXII)                       |
| Дельт                   | D1–D6                       | D7–D14                              |
| Гипотез                 | 9 (неструктурированные)     | 11 (APV Cards v1.2.1, preregistered)|
| Пилотный протокол       | Sketch (Часть VII, N=6–12)  | Full (v1.0, N=160, hybrid SCED+Group)|
| Evidence Map             | Отсутствует                 | 3 блока, 11 гипотез, 50+ ссылок    |
| Оригинальные NOT TESTED | Не выделены                 | 4 гипотезы формально идентифицированы|
| Фальсификация           | P0 kill criteria (общие)    | Per-hypothesis fail thresholds      |

---

# ДЕЛЬТЫ D7–D14

## D7. ЧАСТЬ XXII: ТЕРМОДИНАМИКА БЫТИЯ (НОВЫЙ РАЗДЕЛ)
**Файл:** HBP_SystemMap_v1.4_Part_XXII_T2.md
**Объём:** ~19 500 символов
**Содержание:**

Полная формализация моста Пригожин → FEP → Рыжов → HBP:

- 22.1: Диссипативные структуры, NESS, субъект как dissipative structure
- 22.2: FEP как формальный мост (F_var ≈ F_thermo), конструал-дисклеймер (П4, П12)
- 22.3: Потребности Рыжова как prior preferences, маппинг на 6 FM, chronic PE
- 22.4: **Двойная модель патологии** (NESS breakdown vs Attractor trapping) — ОРИГИНАЛ HBP
- 22.5: CSD и фазовые переходы (downgraded to exploratory)
- 22.6: Неравновесная физика мозга — новый evidence (arXiv 2025)
- 22.7: Интеграционная схема (полная)
- 22.8: Проверка непротиворечивости: 14/14 постулатов ✅
- 22.9: Ограничения (5 пунктов)
- 22.10: Публикационный потенциал

**Источники:** DR2 (HBP-DR2-Prigogine-FEP.md), arXiv 2025 (nonequilibrium brain dynamics),
Lövdén et al. 2025 (CSD sensitivity), Friston 2013, Ramstead 2018, Friston 2023.

**Непротиворечивость с ядром:** 14/14 ✅

---

## D8. КОРРЕКЦИЯ ЧАСТИ IV (ЭТИОЛОГИЯ): AVOIDANCE = ПРЕДИКТОР, НЕ МОДЕРАТОР
**Затрагивает:** Часть IV (этиология), Часть XIV (клинические импликации)
**Источник:** Evidence Map Block 2, Zilcha-Mano (2022)

**Было (v1.3):**
Attachment pattern модерирует исход терапии (r=0.35, N=3158) — без разделения
на anxiety vs avoidance.

**Стало (v1.4):**
- Attachment ANXIETY = модератор связи alliance → outcome (B=.09, p=.016)
- Attachment AVOIDANCE = прямой предиктор скорости ответа (NOT модератор; p=.57 для модерации)
- FEP-интерпретация (оригинальная HBP): avoidance = deactivated PE-processing →
  slower updating of generative model → slower symptom change

**Где менять в System Map:**
- Часть III (столпы): добавить Zilcha-Mano 2022 в Tier 1 «Онтогенез priors»
- Часть XIII (Attachment через FEP): разделить Avoidant A на предиктор (slope) vs
  Anxious C на модератор (alliance × outcome)
- Часть XIV (клинические импликации): обновить прогнозы по attachment

---

## D9. КОРРЕКЦИЯ ЧАСТИ IX/XIV: TRUST → MISTRUST
**Затрагивает:** Часть IX (П9), Часть XIV, Часть VII (батарея)
**Источник:** Evidence Map Block 2, Campbell & Allison (2021), Riedl (2024)

**Было (v1.3):**
П9 описывает: «Рабочие шкалы: Mistrust и Credulity (НЕ Trust; r = 0.12 — не работает)»
→ Это уже КОРРЕКТНО в v1.3! Коррекция Trust → Mistrust была внесена ранее.

**Стало (v1.4, уточнение):**
Добавить WARNING: Riedl (2024) — ET не изменился за курс реабилитации.
→ ETMCQ sensitivity to change под вопросом.
→ Пилотный протокол включает Step 0: тест sensitivity ETMCQ-R pre→mid.

**Где менять:**
- П9 (Часть II): добавить предупреждение Riedl 2024
- Часть VII (батарея): ETMCQ-R — добавить пометку «Step 0 sensitivity test required»
- Часть XIX (пробелы): добавить «ETMCQ-R sensitivity — открытый вопрос»

---

## D10. КОРРЕКЦИЯ ЧАСТИ VII (БАТАРЕЯ): ΔHRV → EXPLORATORY
**Затрагивает:** Часть VII (батарея), Часть V (модель здоровья)
**Источник:** Evidence Map Block 3, Wang et al. (2025)

**Было (v1.3):**
HRV: RMSSD, HF-power (5 мин, 4×/нед) — без указания статуса confirmatory/exploratory.

**Стало (v1.4):**
- Baseline RMSSD = **confirmatory** predictor (g = −0.58 transdiagnostic, Alvares 2016)
- ΔHRV (pre→post) = **exploratory** (Wang 2025 umbrella: Grade IV, weak evidence)
- HRV moderator = **exploratory** (HRV определяет тип оптимального лечения, Mathersul 2024)

**Где менять:**
- Часть VII: пометить ΔHRV как exploratory; baseline RMSSD как confirmatory
- Часть V (C+F+R): RMSSD остаётся маркером Resilience, но с caveat на ΔHRV

---

## D11. КОРРЕКЦИЯ ЧАСТИ VII (БАТАРЕЯ): MAIA-2 SUBSCALE REFINEMENT
**Затрагивает:** Часть VII (батарея)
**Источник:** Evidence Map Block 3, Knep & Shires (2025), Price et al. (2024)

**Было (v1.3):**
MAIA-2 Brief (интероцепция: Noticing + Trusting, 8 пп.)

**Стало (v1.4):**
- **Body Listening = primary mediator** (Knep 2025: β = −.76 для MBI → depression)
- Trusting: НЕ медиировал симптомы (p = .532)
- Self-Regulation: наибольший d в MBI
- Полная MAIA-2 (37 items) в пилоте, focus: Body Listening, Trusting, Self-Regulation
- Brief version для session-level: оставить Noticing + Body Listening (не Trusting!)

**Где менять:**
- Часть VII: обновить MAIA-2 Brief → Noticing + Body Listening; полная = 37 items
- Часть VII (пилот): заменить focus subscales

---

## D12. КОРРЕКЦИЯ ЧАСТИ IV/VII: BDNF DOWNGRADED, TISSUE SPECIFICITY
**Затрагивает:** Часть IV (эпигенетика), Часть VII (батарея)
**Источник:** Evidence Map Block 3, Piotrkowicz (2021), Hummel (2022), Quevedo (2022)

**Было (v1.3):**
Methylation assays: FKBP5, SLC6A4, NR3C1 (без BDNF-caveat, без tissue specificity)

**Стало (v1.4):**
- **FKBP5 + NR3C1 = primary targets** (strongest evidence)
- **BDNF downgraded** (only 3/9 positive; Hummel 2022: null in monocytes)
- **Tissue specificity**: saliva > blood > monocytes
- **Differential susceptibility formalized**: FKBP5 change ONLY with early trauma (Quevedo 2022)
  → Hardware × Input interaction
- **SLC6A4**: pharmacotherapy only (Domschke 2021) → не для D-HBP пилота

**Где менять:**
- Часть IV (эпигенетика): добавить tissue caveat, BDNF downgrade, differential susceptibility
- Часть VII (батарея): Saliva DNA → focus FKBP5 intron 7 + NR3C1 exon 1F; BDNF → exploratory
  only if budget allows

---

## D13. КОРРЕКЦИЯ ЧАСТИ XIX (ПРОБЕЛЫ): ОБНОВЛЕНИЕ СТАТУСА
**Затрагивает:** Часть XIX

**Новые закрытые пробелы (v1.4):**

| # | Пробел | Закрыт в | Как |
|---|--------|----------|-----|
| 45 | Термодинамика Пригожин → FEP → HBP | D7, Часть XXII | Полный раздел T2 |
| 46 | APV Cards (структурированные гипотезы) | APV Cards v1.2.1 | 11 гипотез, preregistration-ready |
| 47 | Evidence Map | Evidence Map Blocks 1–3 | 3 блока, 50+ ссылок, 8 коррекций |
| 48 | Пилотный протокол (полный) | D-HBP Pilot Protocol v1.0 | Hybrid SCED+Group, N=160, 18 инструментов |
| 49 | Per-hypothesis falsification | APV Cards v1.2.1 | Confirm/fail thresholds для каждой H |
| 50 | Оригинальные NOT TESTED гипотезы | Evidence Map | 4 гипотезы идентифицированы |

**Оставшиеся пробелы (для v1.5+):**

| # | Пробел | Приоритет | Комментарий |
|---|--------|-----------|-------------|
| 51 | Глоссарий (114 терминов, рус/англ) | HIGH | Давно запланирован, быстро делается |
| 52 | D-HBP мануал (полный, сессия-за-сессией) | HIGH | Нужен для обучения терапевтов пилота |
| 53 | Этический кодекс HBP | MEDIUM | Нужен до запуска пилота |
| 54 | Флагманская статья (peer-reviewed, English) | HIGH | Целевой журнал TBD |
| 55 | SDT маппинг на FM4–FM6 | LOW | Дополнение к модели |
| 56 | Нарративная психология (Брунер) | LOW | За пределами White & Epston |
| 57 | OSF preregistration | HIGH | Залить Protocol + APV Cards |
| 58 | Русская валидация инструментов | HIGH | ETMCQ-R, Psy-Flex, LEIDS-R, ORS/SRS |
| 59 | System Map v1.4 — применение всех D8–D12 в теле документа | HIGH | Текущий changelog фиксирует ЧТО; нужно внести в PDF |

---

## D14. ЧАСТЬ XXI (CHANGELOG): РАСШИРЕНИЕ
**Затрагивает:** Часть XXI

Добавить в Часть XXI записи D7–D13 (этот документ).

---

# СВОДНАЯ ТАБЛИЦА ВСЕХ ДЕЛЬТ v1.3 → v1.4

| Дельта | Тип | Часть | Описание | Источник |
|--------|-----|-------|----------|----------|
| D7 | НОВЫЙ РАЗДЕЛ | XXII | Термодинамика бытия: Пригожин → FEP → HBP | DR2 + arXiv 2025 |
| D8 | КОРРЕКЦИЯ | IV, XIII, XIV | Avoidance = предиктор, не модератор | Zilcha-Mano 2022 |
| D9 | УТОЧНЕНИЕ | II (П9), VII, XIX | ETMCQ sensitivity warning (Riedl 2024) | Evidence Map Block 2 |
| D10 | КОРРЕКЦИЯ | VII, V | ΔHRV → exploratory; baseline → confirmatory | Wang 2025 |
| D11 | КОРРЕКЦИЯ | VII | MAIA-2: Body Listening = primary; Trusting ≠ mediator | Knep 2025 |
| D12 | КОРРЕКЦИЯ | IV, VII | BDNF downgraded; tissue specificity; differential susceptibility | Piotrkowicz 2021, Hummel 2022, Quevedo 2022 |
| D13 | ОБНОВЛЕНИЕ | XIX | 6 пробелов закрыто; 9 новых идентифицировано | All new files |
| D14 | ОБНОВЛЕНИЕ | XXI | Changelog D7–D13 добавлен | This document |

---

# ФАЙЛЫ ПРОЕКТА HBP (полный реестр после v1.4)

## Ядро парадигмы
| # | Файл | Версия | Статус |
|---|------|--------|--------|
| 1 | HBP-System-Map-v1.3-FINAL.pdf | v1.3 | Текущий baseline |
| 2 | HBP_SystemMap_v1.4_Part_XXII_T2.md | v1.4 D7 | Новый раздел |
| 3 | HBP_SystemMap_v1.4_Changelog.md | v1.4 | **Этот документ** |

## Deep Research
| # | Файл | Содержание |
|---|------|-----------|
| 4 | HBP-DR2-Prigogine-FEP.md | DR2: Пригожин × FEP × Рыжов |
| 5 | (DR1, DR3, DR4 — в предыдущих чатах) | Теоретическая сеть, другие модули |

## Evidence & Validation
| # | Файл | Содержание |
|---|------|-----------|
| 6 | HBP_Evidence_Map_Blocks_1-3.md | Карта доказательств: 3 блока, 11 гипотез |
| 7 | HBP_APV_Cards_v1.2.1.md | Assumption–Prediction–Validation карточки |

## Пилотный протокол
| # | Файл | Содержание |
|---|------|-----------|
| 8 | D-HBP-Pilot-Protocol.md | Полный протокол v1.0 (Registered Report ready) |

---

# ПРОВЕРКА ЦЕЛОСТНОСТИ

## Внутренняя непротиворечивость D7–D14 с ядром

| Проверка | Результат |
|----------|-----------|
| D7 (Часть XXII) ↔ 14 постулатов | ✅ 14/14 (проверено в 22.8) |
| D8 (Avoidance) ↔ П5 (Active Inference) | ✅ Avoidance = deactivated PE = consistent |
| D8 (Avoidance) ↔ П7 (Иерархия значимости) | ✅ Attachment = high-significance relationship |
| D9 (Mistrust) ↔ П9 (Epistemic trust) | ✅ П9 уже корректен в v1.3 (Mistrust > Trust) |
| D10 (ΔHRV) ↔ П2 (Субстрат) | ✅ HRV = substrate marker; downgrade = epistemically honest |
| D11 (MAIA-2) ↔ П5 (Active Inference) | ✅ Body Listening = interoceptive PE-processing |
| D12 (Epigenetics) ↔ Часть IV (Этиология) | ✅ Эпигенетика = мост HW↔Input, уточнена |
| D7 ↔ APV Cards v1.2.1 | ✅ Двойная модель → interaction HRV × PFS (exploratory) |
| D7 ↔ Pilot Protocol v1.0 | ✅ CSD = exploratory (consistent); dynamic complexity = primary |
| APV Cards ↔ Pilot Protocol | ✅ Все 7 Tier 1 + 3 Tier 2 + 1 Tier 3 покрыты |

## Рассогласования обнаружены

| # | Рассогласование | Серьёзность | Решение |
|---|----------------|-------------|---------|
| 1 | System Map v1.3 (Часть VII): MAIA-2 Brief = «Noticing + Trusting»; Evidence Map: Trusting НЕ медиирует | MEDIUM | D11: исправить на Noticing + Body Listening |
| 2 | System Map v1.3 (Часть VII): пилот N=6–12; Pilot Protocol: N=160 | LOW (superseded) | Pilot Protocol v1.0 = authoritative source; System Map пилот = outdated sketch |
| 3 | System Map v1.3: LEIDS-R в батарее как «type-2 precision proxy»; APV v1.2.1: LEIDS-R = Software-proxy (H3, не H1) | LOW | D11-adjacent: обновить в Часть VII при сборке v1.4 |

Все 3 рассогласования = LOW–MEDIUM, разрешаются при сборке полного v1.4 PDF.

---

# ROADMAP v1.4 → v1.5

| Этап | Что | Когда | Кто |
|------|-----|-------|-----|
| 1 | Глоссарий (114 терминов) | Следующая сессия | AI + Александр |
| 2 | Сборка v1.4 PDF (D7–D14 применены в тело) | После глоссария | AI |
| 3 | OSF preregistration (Protocol + APV) | Q1 2026 | Александр |
| 4 | D-HBP мануал (полный) | Q2 2026 | Александр + AI |
| 5 | Русская валидация инструментов | Q2 2026 | Research team |
| 6 | Флагманская статья (English) | Q3 2026 | Александр + AI |

---

# КОНЕЦ CHANGELOG v1.3 → v1.4
