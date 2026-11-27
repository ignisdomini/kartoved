<p align="center"><img src="docs/promo/social-preview-ru.png" alt="КАРТОВЕДЪ — старинные карты России" width="860"></p>

<p align="center">
<b>Русский</b> · <a href="README.en.md">English</a>
</p>

# КАРТОВЕДЪ — старинные карты России

Тысячи старинных карт России на телефоне и компьютере: планы Генерального межевания XVIII века, карты Шуберта и Стрельбицкого, губернские атласы, топография XX века. Лист скачивается один раз, ложится поверх спутника и дальше работает без интернета.

**Бесплатно. Без рекламы. Без подписок и встроенных покупок.** Проект существует с 2006 года.

## ⬇ Скачать

| Платформа | Версия | Файл | Требования |
|---|---|---|---|
| **Android** | 1.5.1 | [**KARTOVED.apk**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED.apk) · 14,4 МБ | Android 8.0+ |
| **Windows** — установщик | 1.5.2 | [**KARTOVED-Setup.exe**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED-Setup.exe) · 127 МБ | Windows 10/11, 64 бит |
| **Windows** — без установки | 1.5.2 | [**KARTOVED-Portable.zip**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED-Portable.zip) · 149 МБ | Windows 10/11, 64 бит |

Все версии и контрольные суммы — в разделе [Релизы](https://github.com/ignisdomini/kartoved/releases). Те же файлы — на сайте [kartoved.ru/app.php](https://kartoved.ru/app.php).

В репозитории публикуются только готовые сборки и описание. Исходный код закрыт, см. [лицензию](LICENSE.md).

---

## Android

<p>
<img src="docs/android/01-karta-sputnik.jpg" width="160">
<img src="docs/android/05-sentinel-ndvi.jpg" width="160">
<img src="docs/android/07-gps-kompas.jpg" width="160">
<img src="docs/android/08-pogoda.jpg" width="160">
<img src="docs/android/10-monety.jpg" width="160">
</p>

**Карты**
- Каталог старинных карт по эпохам и сериям, поиск. Лист скачивается один раз и открывается в поле без связи.
- Наложение на спутник с прозрачностью, правка привязки листа пальцем.
- Свои карты: OziExplorer, KMZ/KML, MBTiles, OruxMaps, SQLiteDB. Листы в СК-42 пересчитываются сами.
- Слои OpenStreetMap: памятники археологии, урочища, исторические места, охранные зоны — офлайн-пакетом на всю Россию.

**Снимки Sentinel-2.** Естественные и ложные цвета, NDVI, NDRE, влажность почвы с 2017 года. По растительности видны следы засыпанных рвов, валов, дорог и фундаментов. Снимки обрабатываются на телефоне, ключи не нужны.

**Приборы.** GPS Компас (GPS, ГЛОНАСС, Galileo, BeiDou на астролябии и оценка точности), погода на 10 дней с подсказками для поля, АРХЕОСКАН, APEX DSP.

**Новое в 1.5.** Вступление в организации поисковиков (МПР и ФППР) и членский билет без сети; заявление о находке по бланку организации — PDF, DOC, печать, почта; журнал находок со слоем «Находки» на карте и выгрузкой в GPX, KML, KMZ, GeoJSON, CSV; поиск места по названию и координатам; «Забыли пароль?». Находки и заявления хранятся только на устройстве.

**В поле.** Навигация к точке, GPS-трекер с погашенным экраном, метки с фото, обмен GPX / KML / KMZ, справочник «Монеты России», чат и доска объявлений.

<details>
<summary>Все скриншоты Android</summary>

| | | | | |
|---|---|---|---|---|
| ![](docs/android/01-karta-sputnik.jpg) | ![](docs/android/02-karta-prozrachnost.jpg) | ![](docs/android/03-privyazka.jpg) | ![](docs/android/04-svoi-karty.jpg) | ![](docs/android/05-sentinel-ndvi.jpg) |
| ![](docs/android/06-sentinel-panel.jpg) | ![](docs/android/07-gps-kompas.jpg) | ![](docs/android/08-pogoda.jpg) | ![](docs/android/09-pogoda-10-dnej.jpg) | ![](docs/android/10-monety.jpg) |

</details>

## Windows

<p><img src="docs/promo/windows-banner.jpg" width="720"></p>

Всё главное из Android — на большом экране:
- каталог старинных карт, наложение на спутник, правка привязки листа;
- **модуль привязки**: своя картинка (скан, фото карты) накладывается на местность по точкам и сохраняется в .sqlitedb, KML, OruxMaps, Ozi;
- импорт чужих карт, снимки Sentinel-2, погода, АРХЕОСКАН, APEX DSP, небесная карта;
- метки, маршруты, галерея, справочник монет, чат и объявления;
- автообновление с сайта.

<details>
<summary>Скриншоты Windows</summary>

| | |
|---|---|
| ![](docs/windows/slide-1-maps.jpg) | ![](docs/windows/slide-2-layers.jpg) |
| ![](docs/windows/w13-sentinel.jpg) | ![](docs/windows/w13-weather.jpg) |
| ![](docs/windows/w12-import.jpg) | ![](docs/windows/w12-coins.jpg) |
| ![](docs/windows/slide-4-scan.jpg) | ![](docs/windows/w13-apex.jpg) |
| ![](docs/windows/slide-3-sky.jpg) | ![](docs/windows/slide-5-chat.jpg) |

</details>

---

## Установка

**Android.** Скачайте `KARTOVED.apk`, откройте файл на телефоне и разрешите установку из этого источника. Новая версия ставится поверх прежней — с сайта, из этого репозитория или из магазина.

**Windows.** Запустите `KARTOVED-Setup.exe`. У программы пока нет подписи кода, поэтому Windows SmartScreen может предупредить: «Подробнее» → «Выполнить в любом случае». Переносная версия: распакуйте `KARTOVED-Portable.zip` в любую папку и запустите `KARTOVED.exe`.

**Проверка подлинности.** В каждом релизе есть `SHA256SUMS.txt`. Подпись Android-сборок: `CN=KARTOVED`, SHA-1 `f5:af:f3:42:0c:06:81:4f:d5:c9:f9:f6:ef:d0:be:2d:e9:e7:a4:0f`.

**Автообновление Android без магазина** — через [Obtainium](https://github.com/ImranR98/Obtainium): добавьте адрес `https://github.com/ignisdomini/kartoved`.

## Учётная запись

Регистрация бесплатная — в приложении (Кабинет) или на [kartoved.ru](https://kartoved.ru/register.php). Без входа доступна карта-спутник; каталог карт, приборы, чат и объявления — после входа.

## Данные и приватность

Метки, маршруты и свои карты хранятся только на устройстве. Для прогноза погоды координаты округляются до клетки около 5 км. Рекламы и сторонней аналитики нет.
[Политика конфиденциальности](https://kartoved.ru/privacy.php) · [удаление учётной записи](https://kartoved.ru/account.php#delete)

Приложение — инструмент краеведа и историка. Поиск и изъятие предметов из культурного слоя без открытого листа запрещены законом (ст. 243.2 УК РФ).

## Связь

Апостол Андрей Витальевич · apostolgroup@gmail.com · [kartoved.ru](https://kartoved.ru)

Сообщить об ошибке можно в разделе [Issues](https://github.com/ignisdomini/kartoved/issues) или письмом.

---

© 2006–2026 Проект КАРТОВЕДЪ. Все права защищены. Бесплатная лицензия на использование — [LICENSE.md](LICENSE.md).
Данные: © участники OpenStreetMap (ODbL) · Contains modified Copernicus Sentinel data · погода Open-Meteo (CC BY 4.0) · подложка Esri.
