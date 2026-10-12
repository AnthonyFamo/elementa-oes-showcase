# Changelog / История версий

Versions are **0.X.Y** while the program is a prototype; 1.0 will be the first release.
*Пока программа — опытный образец, номер версии 0.X.Y; 1.0 — первый выпуск.*

## 0.17.0 — 2026-10-12 — drawing tools and value formatting / рисование и оформление значений

**English**
- Shapes are placed with the mouse: click to drop one, or drag to size it like in Paint. A single free-angle arrow; lines stay horizontal or vertical.
- Line breaks and lists (1. / 1) / ▪) in text boxes, callouts and the note; callout leader starts at the frame edge.
- The selected element is shown with a dashed outline; field names and field values are formatted separately (strikethrough, superscript, subscript added).
- More fonts, including Chinese, Japanese and Korean; Word-style alignment icons.
- Composition table: light borderless cells by default, choice of separation style and fills for headers, base and cells.

**По-русски**
- Фигуры ставятся мышью: щелчок — на место, протягивание — с размером, как в Paint. Одна стрелка под любым углом; линии — только горизонтальные или вертикальные.
- Перевод строки и списки (1. / 1) / ▪) в надписи, сноске и примечании; выноска сноски — от края рамки.
- Выбранный элемент — в пунктирной рамке; название и значение поля оформляются отдельно (добавлены зачёркнутый, надстрочный, подстрочный).
- Больше шрифтов, в том числе китайские, японские, корейские; значки выравнивания как в Word.
- Таблица состава: по умолчанию светлые ячейки без рамок, выбор вида разделения и заливки заголовков, основы и ячеек.

## 0.16.0 — 2026-10-12 — in-place template editor / редактор внутри окна шаблона

**English**
- The page editor opens inside the template window (full app size) instead of a separate window.
- Shapes are drawn over the page and move smoothly; a callout's box and pointer tip are dragged independently; vertical line; consistent icons; delete from the list.
- Field values (sample, grade, notes, analysis fields) are editable in the preview; Ctrl + mouse wheel zoom 50–200 %; 36-colour palette.
- Composition table: centred text, rounded cells, clearer borders, adjustable row height.

**По-русски**
- Редактор листа открывается внутри окна шаблона (на весь экран программы), а не отдельным окном.
- Фигуры рисуются поверх листа и двигаются плавно; у сноски рамка и точка выноски перетаскиваются отдельно; вертикальная линия; иконки в общем стиле; удаление из списка.
- В предпросмотре правятся значения (образец, марка, примечания, поля анализа); масштаб Ctrl + колесо 50–200 %; палитра из 36 цветов.
- Таблица состава: текст по центру, скруглённые ячейки, заметные границы, регулируемая высота строк.

## 0.15.0 — 2026-10-12 — template editor / редактор шаблонов

**English**
- WYSIWYG preview and editor: A4 pages, drag-and-drop order of blocks and field rows, fonts, sizes, bold/italic/underline, alignment, colours; logo size; page colour; text or image watermark; shapes — text, line, rectangle, ellipse, arrows in 8 directions, semi-transparent callout — dragged and resized with the mouse; undo/redo; document-only fields.
- Certificate numbers follow the company's own numbering (asked on issue).
- Printing via the standard Windows print dialog; small fixed footer line.
- Field mode polish: Field Reports folders, no scrollbars, full-size buttons.

**По-русски**
- Предпросмотр и редактор: страницы A4, порядок блоков и строк полей перетаскиванием, шрифты, размеры, Ж/К/Ч, выравнивание, цвета; размер логотипа; цвет страницы; водяной знак текстом или картинкой; фигуры — надпись, линия, прямоугольник, эллипс, стрелки в 8 направлениях, полупрозрачная сноска — двигаются и меняют размер мышью; отмена правок; поля «только в документе».
- Номер сертификата — по нумерации предприятия (спрашивается при выдаче).
- Печать через стандартное окно Windows; неизменная нижняя строка мелким шрифтом.
- Полевой режим: папки Field Reports, без полос прокрутки, кнопки на всю область.

## 0.14.0 — 2026-10-12 — report and certificate of conformity / протокол и сертификат соответствия

**English**
- Two documents with separate templates: a detailed analysis report (lab) and a certificate of conformity to the declared grade (customer).
- Grade limits and verdict from the grade library (case-insensitive, Latin/Cyrillic look-alike letters and former grade names); if the grade is unknown, the operator chooses the verdict.
- Composition table horizontal (element columns in blocks, like classic OES software) or vertical; excluded burns struck through; above / below limit in red ↑ / blue ↓; base element per burn.
- Lab header from separate address fields, resizable logo, QR code, Code 128 sample barcode; live page preview.
- Results export to CSV, Excel and TXT (choice of separator).
- Burn buttons: exclude / delete, restore the last 3 deleted; change the analytical program inside the analysis with recalculation; operator name list with suggestions.
- Field mode reworked: bigger controls, mouse tilt-wheel and touch paging, optional statistics columns.

**По-русски**
- Два документа со своими шаблонами: подробный протокол анализа (лаборатория) и сертификат соответствия заявленной марке (заказчик).
- Нормы и вердикт — по марочнику (без учёта регистра, похожих русских и латинских букв и прежних названий марок); марки нет — решение выбирает оператор.
- Таблица состава горизонтально (элементы столбцами блоками) или вертикально; выброшенные прожиги зачёркнуты; выше / ниже нормы — красным ↑ / синим ↓; основа и по прожигам.
- Шапка из отдельных строк реквизитов, логотип с настраиваемым размером, QR-код, штрих-код образца Code 128; предпросмотр листа.
- Результаты в CSV, Excel и TXT (с выбором разделителя).
- Кнопки у прожигов: выбросить / удалить, вернуть 3 последних удалённых; смена подпрограммы прямо в анализе с пересчётом; список фамилий операторов с подсказками.
- Полевой режим переработан: крупные кнопки, листание боковым колесом мыши и пальцем, дополнительные столбцы статистики.

## 0.13.0 — 2026-10-11 — certificate of analysis / сертификат анализа

**English**
- Certificate of analysis (A4): lab header and logo, number and date, analysis fields, target grade, per-burn values, mean and expanded uncertainty ±U (k = 2), signatures, QR code, footer with program and instrument data. Export to PDF, HTML, TXT, CSV and Excel; printing.
- SD and RSD columns are optional in the report template; a legend explains the symbols.
- Custom analysis fields: text, list, number, date, auto-numbered counter (per year); required fields, “in report”, and a 🔒 “remember” lock that carries the value to the next sample.
- Report template editor: organisation, logo, title, note, signatures, columns, font and colour, preview; templates are exchanged as `.eltmpl` files.
- All new texts in 14 languages.

**По-русски**
- Сертификат анализа (A4): шапка лаборатории с логотипом, номер и дата, поля анализа, марка-задание, значения по прожигам, среднее и расширенная неопределённость ±U (k = 2), подписи, QR-код, нижняя строка с данными программы и прибора. Выгрузка в PDF, HTML, TXT, CSV и Excel; печать.
- Столбцы СКО и ОСКО — по выбору в шаблоне; под таблицей — расшифровка обозначений.
- Свои поля анализа: текст, список, число, дата, счётчик номера (по годам); обязательные, «в отчёте» и замочек 🔒 «помнить» — значение переходит в следующий анализ.
- Окно шаблона отчёта: организация, логотип, заголовок, примечание, подписи, столбцы, шрифт и цвет, предпросмотр; обмен шаблонами — файлы `.eltmpl`.
- Все новые надписи — на 14 языках.

## 0.12.0 — 2026-10-11 — activity log / журнал действий

**English**
- Activity log: who did what and when — sign-ins and passwords, programs, calibrations, reference materials, instrument, backups, analyses. Stored in the encrypted instrument database; records are chained with SHA-256 hashes, so editing or deleting them outside the program is detected. Filters by period, section and text, CSV export.
- Technical log split by month and kept for 13 months.

**По-русски**
- Журнал действий: кто, когда и что сделал — вход и пароли, программы, градуировки, стандартные образцы, прибор, резервные копии, анализы. Хранится в зашифрованной базе прибора; записи связаны цепочкой отпечатков SHA-256 — правка или удаление в обход программы обнаруживаются. Фильтры по периоду, разделу и тексту, выгрузка в CSV.
- Технический журнал — по месяцам, хранится 13 месяцев.

## 0.11.0 — 2026-10-11 — role passwords / пароли ролей

**English**
- Operator works without a password; engineer and master roles require passwords (stored only as PBKDF2 hashes inside the encrypted instrument database).
- The master sets the engineer password.
- The master password is set — or recovered — with a challenge–response code: the program shows a short request code, the master's separate generator answers with an ECDSA digital signature. The program holds only the public key, so the response cannot be forged even by taking the program apart; the generator is compiled to native code.

**По-русски**
- Оператор работает без пароля; роли инженера и мастера — по паролю (хранятся только отпечатки PBKDF2 в зашифрованной базе прибора).
- Пароль инженера задаёт мастер.
- Пароль мастера задаётся и восстанавливается кодом «запрос — ответ»: программа показывает короткий код-запрос, отдельный генератор мастера отвечает цифровой подписью ECDSA. В программе только открытый ключ — ответ не подделать даже разобрав программу; генератор собран в машинный код.

## 0.10.0 — 2026-10-11 — 14 languages, translated program names, UI polish / 14 языков, названия программ на языках, доработка интерфейса

**English**
- Spanish and Portuguese added — 14 interface languages in total.
- Analytical program names are translated too: factory programs (cast irons, stainless, free-cutting steels…) come in all 14 languages; user-created ones can be renamed per language.
- Consistent tiles on the start screen, cleaner status bar, a single role indicator, a more readable notification, an updated "About" window with the actual Windows version.
- The installer runs in 10 languages.

**По-русски**
- Добавлены испанский и португальский — всего 14 языков интерфейса.
- Названия аналитических программ тоже переводятся: заводские (чугуны, нержавеющие, автоматные стали…) — на всех 14 языках, свои можно переименовать на каждом языке.
- Единые плитки на стартовом экране, чище строка состояния, роль показана в одном месте, заметнее уведомления, обновлённое окно «О программе» с реальной версией Windows.
- Установщик — на 10 языках.

## 0.9.0 — 2026-10-11 — 12 languages / 12 языков

**English**
- Interface translated into 12 languages: Russian, English, Italian, French, German, Chinese (Traditional and Simplified), Japanese, Korean, Polish, Uzbek, Kazakh (machine-drafted, to be reviewed by native speakers).
- The language switches instantly, without a restart.
- Button labels wrap only at spaces and hyphens, so CJK labels are not broken mid-word; an automated test checks label length in every language.
- The installer ships the Visual C++ runtime next to the program and runs in 8 languages — nothing to install beforehand on a clean Windows PC.

**По-русски**
- Интерфейс на 12 языках: русский, английский, итальянский, французский, немецкий, китайский (традиционный и упрощённый), японский, корейский, польский, узбекский, казахский (машинный черновик, проверят носители языка).
- Язык меняется сразу, без перезапуска.
- Подписи кнопок переносятся только по пробелам и дефисам — иероглифы не рвутся посреди слова; тест проверяет длину надписей во всех языках.
- Установщик кладёт Visual C++ Runtime рядом с программой и работает на 8 языках — на «чистой» Windows ничего ставить заранее не нужно.

## 0.8.0 — 2026-10-11 — installer / установщик

**English**
- Windows installer (Inno Setup), Russian and English: install for all users or just for the current user; the runtime ships with the program.
- Optional database viewer component, downloaded during installation.
- USB workflow: put the installer and the instrument's backup on a stick — after installation the program finds the backup at first start and only asks for its password.
- Program files open by double-click (backups, subprograms, reference materials, spectra, analyses); a single running instance receives them.

**По-русски**
- Установщик для Windows (Inno Setup), русский и английский: для всех пользователей или только для себя; среда выполнения — вместе с программой.
- По желанию — программа просмотра базы, скачивается при установке.
- Работа с флешкой: установщик и резервная копия прибора рядом — после установки программа сама находит копию при первом запуске и спрашивает только пароль.
- Файлы программы открываются двойным щелчком (копии, подпрограммы, стандартные образцы, спектры, анализы); работает одна копия программы.

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
