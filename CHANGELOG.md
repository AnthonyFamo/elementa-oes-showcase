# Changelog / История версий

Versions are **0.X.Y** while the program is a prototype; 1.0 will be the first release.
*Пока программа — опытный образец, номер версии 0.X.Y; 1.0 — первый выпуск.*

## 0.5.0 — 2026-10-11 — database and backup / база данных и резервная копия

**English**
- All program data in one place, the program's own Data folder: an SQLite database (analyses and every burn spectrum, compressed), settings, reference materials, methods, log.
- Spectra are tagged by purpose (analysis, calibration, standardisation, recalibration, service).
- One-file backup (.ebak) for engineers: calibration data is always included, routine analyses optionally; restore on restart keeps the previous data aside.
- Analyses are searched and opened from the database.
- "About" window: version, licence, instrument adapter, data location, developer.
- Mock-ups of the analysis certificate, the report template editor and user-defined analysis fields.

**По-русски**
- Все данные — в собственной папке программы Data:
  - база SQLite: анализы и спектры всех прожигов (в сжатом виде);
  - настройки, стандартные образцы, методики, журнал.
- У каждого спектра есть назначение: анализ, градуировка, стандартизация, рекалибровка, сервис.
- Резервная копия одним файлом (.ebak), делает инженер:
  - данные градуировок входят всегда;
  - анализы образцов — по выбору.
- Восстановление — при перезапуске; прежние данные сохраняются рядом.
- Поиск и открытие анализов из базы.
- Окно «О программе»: версия, лицензия, адаптер прибора, где лежат данные, разработчик.
- Макеты сертификата анализа, редактора шаблона отчёта и настраиваемых полей анализа.

## 0.4.0 — 2026-10-11 — calibration and reference materials / градуировки и база СО

**English**
- Calibration curves: linear, through zero, quadratic, square root; any of them in log-log coordinates.
- Valid concentration range and recalibration (drift correction by reference samples).
- Concentrations per burn, normalisation of concentrations relative to the alloy base, element value averaged over its lines, base element = 100 % − sum.
- Verified number for number against the reference implementation on real methods: 67 curves rebuilt bit-exactly; thousands of concentrations equal to the last digit.
- Calibration screen: reference samples of the method, burning a selected sample, certified vs calculated composition, curve plot with points that can be excluded, curve type, formula and statistics.
- Reference materials database: groups → sets → samples with certified values and uncertainties, certificate, producer and expiry date; CSV import/export for Excel; adding samples to a method.

**По-русски**
- Градуировочные кривые: прямая, через ноль, парабола, корень; любая — в логарифмах.
- Допустимый диапазон концентраций и рекалибровка — поправка дрейфа по образцам.
- Расчёт концентраций:
  - по каждому прожигу;
  - нормировка концентраций относительно основы;
  - концентрация элемента — среднее по его линиям;
  - основа — 100 % минус сумма остальных.
- Сверка с эталонной реализацией на настоящих методиках:
  - 67 кривых построены бит в бит;
  - тысячи концентраций совпали до последнего знака.
- Экран «Градуировка»:
  - СО методики и прожиг выбранного СО;
  - сравнение аттестованного и посчитанного состава;
  - график кривой: точки можно исключать;
  - вид кривой, формула, статистика.
- База стандартных образцов:
  - группы → комплекты → образцы;
  - аттестованные значения и погрешности, свидетельство, изготовитель, срок;
  - импорт и экспорт CSV для Excel;
  - добавление СО в методику.

## 0.3.0 — 2026-10-10 — new user interface / новый интерфейс

**English**
- Program named **Elementa OES**, new icon (OES letters over an emission-line spectrum).
- New UI:
  - start screen;
  - lab analysis screen with a ribbon and side rail;
  - field mode with large controls;
  - instrument check screen.
- Sample analysis:
  - burns as columns with mean, SD, RSD, min, max;
  - manual rejection of a burn, automatic rejection when there was no spark.
- Saving and opening analyses (JSON), recalculation with the current method, CSV export.
- Engineer view: spectrum around the selected line, values per burn, drift, spectrum state.
- Burn-quality indicator in the status bar.
- Roles: operator, engineer, master.
- Themes: light, dark, system.

**По-русски**
- Программа получила название **Elementa OES** и иконку: буквы OES над спектром с линиями испускания.
- Новый интерфейс:
  - стартовый экран;
  - лабораторный экран анализа с лентой и боковой панелью;
  - полевой режим с крупными кнопками;
  - экран проверки прибора.
- Анализ образца:
  - прожиги столбцами, среднее, СКО, RSD, мин, макс;
  - ручная отбраковка прожига, автоматическая — если не было искры.
- Сохранение и открытие анализов (JSON), пересчёт по текущей методике, выгрузка в CSV.
- Режим инженера: спектр у выбранной линии, значения по прожигам, дрейф, состояние спектра.
- Индикатор качества прожига в строке состояния.
- Роли: оператор, инженер, мастер.
- Темы: светлая, тёмная, как в Windows.

## 0.2.0 — 2026-10-10 — spectrum processing / обработка спектра

**English**
- Background subtraction, line intensities, peak search, wavelength calibration on reference lines, drift tracking and correction.
- Analysis method file format.
- Every ported algorithm is verified number for number against the reference implementation.

**По-русски**
- Вычитание фона, интенсивности линий, поиск пиков, привязка длин волн по реперам, слежение за дрейфом и его исправление.
- Формат файла методики.
- Каждый перенесённый алгоритм сверен число в число с эталонной реализацией.

## 0.1.0 — core and instrument driver / ядро и драйвер прибора

**English**
- Core spectrum model, instrument driver, network protocol, instrument simulator, instrument check window.

**По-русски**
- Модель спектра, драйвер прибора, сетевой протокол, имитатор прибора, окно проверки прибора.
