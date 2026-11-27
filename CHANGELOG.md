# История версий · Changelog

## Android 1.5.1 · Windows 1.5.2 · 27.11.2026

**RU** Старинные карты стали на уровень чётче. На экранах высокой плотности (телефоны, мониторы с масштабом 150–200 %) приложение растягивало тайл на всю плотность экрана и показывало лист на уровень грубее, чем позволяет экран, — карта выглядела размытой. Теперь пиксель листа близок к пикселю экрана.

**EN** Historical maps are one zoom level sharper. On high-density screens (phones, monitors at 150–200 % scaling) tiles were stretched by the full screen density, showing a sheet a level coarser than the screen allows. Now a sheet pixel is close to a screen pixel.

## Windows 1.5.1 · 22.11.2026

**RU** В Кабинете виден раздел «Организации поисковиков» — вступление в МПР и ФППР и членский билет.

**EN** The "Prospecting organizations" section is now shown in the Cabinet.

## КАРТОВЕДЪ 1.5.0 (Android и Windows) · 22.11.2026

**RU**
- Организации поисковиков: вступление в ОО «Метеорит-Поиск Россия» и ОО «Федерация Приборного Поиска России» из приложения — анкета, фото для удостоверения (в Windows — и с веб-камеры), заявки и реквизиты, Устав. Членский билет во весь экран (в Windows — отдельным окном), работает без сети.
- Заявление о находке по бланку организации: фото, описание, координаты, дата; PDF, DOC, печать, отправка по почте; архив заявлений по датам и просмотр на экране.
- Журнал находок: фото, точка, дата и время, материал и глубина; заявление из отмеченных записей; слой «Находки» на главной карте; выгрузка в GPX, KML, KMZ с фото, GeoJSON и CSV.
- Поиск места по названию (деревни, урочища, реки, улицы), координатам в любом виде и ссылкам Яндекс/Google/OSM; свои метки и находки — без сети.
- «Забыли пароль?» — новый пароль по ссылке из письма; письмо о регистрации.
- Android: главная карта не теряет место при переходах по меню и после перезапуска. Windows: поиск места — Ctrl+F.

**EN**
- Prospecting organizations: join "Meteorite Search Russia" and "Instrument Search Federation of Russia" from the app — form, ID photo (also from the webcam on Windows), orders and payment details, charter. Membership card full screen (a separate window on Windows), works offline.
- Find report on the organization's form: photos, description, coordinates, date; PDF, DOC, print, e-mail; archive by date with on-screen preview.
- Finds log: photo, location, date and time, material and depth; a report from selected entries; "Finds" layer on the home map; export to GPX, KML, KMZ with photos, GeoJSON and CSV.
- Place search by name (villages, tracts, rivers, streets), coordinates in any format and Yandex/Google/OSM links; own waypoints and finds work offline.
- "Forgot password?" via an e-mailed link; welcome e-mail on sign-up.
- Android: the home map keeps its position across menus and restarts. Windows: place search with Ctrl+F.

## КАРТОВЕДЪ 1.4.0 (Android и Windows) · 13.11.2026

**RU**
- «Архив здесь»: какие карты архива есть на этом месте — плашкой на главной, разделом «В этом месте» в каталоге и подсказкой «Вы на скачанном листе» при записи маршрута или навигации. Считается на устройстве, координаты никуда не уходят.
- Обмен между устройствами: метки с фото, маршруты и свои карты — телефон ↔ компьютер и телефон ↔ телефон, файлом .kvpack или по Wi-Fi по одноразовому коду, в шифре.
- Android: обновление прямо из приложения с сайта со сверкой контрольной суммы и подписи; кнопка «Убрать карту» над зумом; привязка своей картинки по точкам.
- АРХЕОСКАН по спектру Sentinel-2 за несколько лет (включается в настройках скана).
- Основа «Спутник Google».
- Чат: ответ на сообщение с цитатой; в Android — вставка из буфера и смайлы.
- Экстренные сообщения проекта и «День поддержки» 1-го числа.
- Windows: разделы открываются после входа, как в телефоне; обновление сверяет контрольную сумму установщика; новое лицензионное соглашение в установщике.

**EN**
- "Archive here": which archive maps cover this place — a chip on the home map, an "At this place" catalogue section and an "You are on a downloaded sheet" hint while recording a track or navigating. Computed on the device; coordinates never leave it.
- Device exchange: waypoints with photos, tracks and own maps — phone ↔ PC and phone ↔ phone, as a .kvpack file or over Wi-Fi with a one-time code, encrypted.
- Android: in-app updates from the website with checksum and signature check; "Hide map" button above zoom; georeferencing your own image by points.
- ARCHEOSCAN with multi-year Sentinel-2 spectra (optional, in scan settings).
- "Google satellite" base map.
- Chat: reply with a quote; on Android — paste from clipboard and emoji.
- Project emergency notices and a monthly "Support day".
- Windows: sections open after signing in, as on the phone; updates verify the installer checksum; new license agreement in the installer.

## Android 1.3.0 · 26.09.2026

**RU**
- Снимки Sentinel-2 на карте: естественные и ложные цвета, NDVI, NDRE, влажность с 2017 года; сохранение участка в «Мои карты»; режим «только по Wi-Fi».
- GPS Компас: спутники GPS, ГЛОНАСС, Galileo, BeiDou на астролябии и оценка точности точки.
- Погода на 10 дней с живым небом и подсказками для поля.
- Справочник «Монеты России».
- Без входа доступна только карта-спутник; остальные разделы — после входа.
- Исправлены вылет при повреждённых данных входа и повторный поиск дат Sentinel.

**EN**
- Sentinel-2 imagery on the map: true/false colour, NDVI, NDRE, moisture since 2017; save areas to "My maps"; Wi-Fi-only mode.
- GNSS Compass: GPS, GLONASS, Galileo, BeiDou on an astrolabe with a position-quality verdict.
- 10-day weather with a live sky and field tips.
- Russian coins reference.
- Without signing in only the satellite map is available.
- Fixed a crash on corrupted login data and Sentinel date re-search.

## Windows 1.3.1 · 06.10.2026

**RU**
- Смайлы в чате, вставка файлов и картинок из буфера обмена (Ctrl+V).
- Исправлена загрузка файлов в чат и объявления.

**EN**
- Emoji in chat, pasting files and images from the clipboard (Ctrl+V).
- Fixed file uploads in chat and classifieds.

## Windows 1.3.0 · 26.09.2026

**RU**
- Снимки Sentinel-2, раздел «Погода», APEX DSP.
- Новый облик: компактное меню, гравюрный логотип, картографическое оформление.

**EN**
- Sentinel-2 imagery, Weather, APEX DSP.
- New look: compact menu, engraved logo, cartographic design.

## Windows 1.2.0 · 24.09.2026
- RU: импорт чужих карт, модуль привязки картинки к местности, автообновление, «Монеты России», правка привязки листа.
- EN: third-party map import, image georeferencing module, auto-update, Russian coins, sheet alignment.

## Android 1.2.0 · 21.09.2026
- RU: навигация к точке и маршруты по дорогам, правка привязки листа, свои карты Ozi/KMZ/MBTiles/OruxMaps, APEX DSP.
- EN: navigation to a point and road routing, sheet alignment, own maps (Ozi/KMZ/MBTiles/OruxMaps), APEX DSP.

## Android 1.1.0 · Windows 1.1.0 · 13–14.09.2026
- RU: небесная карта, чат, доска объявлений, офлайн-слои OSM, GPS-трекер; первая версия для Windows.
- EN: sky map, chat, classifieds, offline OSM layers, GPS tracker; first Windows release.
