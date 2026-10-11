# Changelog / История версий

Versions are **0.X.Y** while the program is a prototype; 1.0 will be the first release.
*Пока программа — опытный образец, номер версии 0.X.Y; 1.0 — первый выпуск.*

## 0.7.0 — 2026-10-11 — data protection, multi-instrument, languages, base detection / защита данных, несколько приборов, языки, определение основы

**English**
- Each instrument's database is an encrypted file (SQLCipher) named by instrument serial number and creation time; per-database keys are protected by Windows (DPAPI).
- Password-protected backups (AES-256 + HMAC, PBKDF2); first start offers to restore the instrument's backup from a USB stick.
- One installation can hold the databases of several instruments: add once from a backup, then switch by selection.
- Exchange files for subprograms, reference materials (plus CSV), spectra and analyses.
- Alloy base detection from the spark spectrum after every burn, with a warning and a suggested switch; "Auto" mode picks the base from the first burn. Matrix-line algorithm: 1091 of 1091 test spectra (Al, Cu, Fe, Ni, Ti alloys) classified correctly.
- Interface translation from a UTF-8 language table (Excel-friendly): Russian and English now, 12 languages planned. Labels adapt to button size (wrap, smaller font, ellipsis with tooltip); a test checks translation length limits.

**По-русски**
- База каждого прибора — зашифрованный файл (SQLCipher), имя — номер прибора и время создания; ключи защищены средствами Windows (DPAPI).
- Резервные копии с паролем; при первом запуске — восстановление копии прибора с флешки.
- В одной программе — базы нескольких приборов: добавить один раз из копии, дальше переключение выбором.
- Файлы обмена: подпрограммы, стандартные образцы (и CSV), спектры, анализы.
- Определение основы сплава по спектру после каждого прожига: предупреждение и предложение сменить подпрограмму; режим «Авто». По матричным линиям: 1091 из 1091 проверочного спектра (Al, Cu, Fe, Ni, Ti) — верно.
- Перевод интерфейса по языковой таблице в UTF-8 (открывается в Excel): сейчас русский и английский, в планах 12 языков. Подписи подстраиваются под кнопку; тест проверяет длину переводов.

## 0.6.0 — 2026-10-11 — programs and subprograms / основы и подпрограммы

**English**
- Analytical methods are stored in the database as programs (alloy base) and subprograms, with full version history; no files to open during work.
- Start screen: pick a base, its subprograms unfold below, then choose lab or field mode.
- Master screen to enable or lock bases and subprograms, copy, rename, reorder, roll back versions, export and import.
- Ready-made subprograms for steels and cast irons, plus "orientation" subprograms for Fe, Cu and Al.

**По-русски**
- Методики хранятся в базе как основы и подпрограммы с полной историей версий; файлы при работе не открываются.
- Стартовый экран: выбрали основу — под ней раскрылись подпрограммы, затем лабораторный или полевой режим.
- Экран мастера:
  - включение и блокировка основ и подпрограмм;
  - копия, переименование, порядок;
  - возврат версии, выгрузка и загрузка файлом.
- Заготовки подпрограмм для сталей и чугунов, ориентационные подпрограммы Fe, Cu и Al.

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
