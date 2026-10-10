# Changelog / История версий

Versions are **0.X.Y** while the program is a prototype; 1.0 will be the first release.
*Пока программа — опытный образец, номер версии 0.X.Y; 1.0 — первый выпуск.*

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
