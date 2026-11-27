<p align="center"><img src="docs/promo/social-preview-en.png" alt="KARTOVED — old maps of Russia" width="860"></p>

<p align="center">
<a href="README.md">Русский</a> · <b>English</b>
</p>

# KARTOVED — Old Maps of Russia

Thousands of historical maps of Russia on your phone and computer: 18th-century General Land Survey plans, Schubert and Strelbitsky maps, provincial atlases, 20th-century topographic sheets. Download a sheet once, overlay it on satellite imagery and use it offline.

**Free. No ads. No subscriptions or in-app purchases.** The project has been running since 2006. The interface is in Russian.

## ⬇ Download

| Platform | Version | File | Requirements |
|---|---|---|---|
| **Android** | 1.5.1 | [**KARTOVED.apk**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED.apk) · 14.4 MB | Android 8.0+ |
| **Windows** — installer | 1.5.2 | [**KARTOVED-Setup.exe**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED-Setup.exe) · 127 MB | Windows 10/11, 64-bit |
| **Windows** — portable | 1.5.2 | [**KARTOVED-Portable.zip**](https://github.com/ignisdomini/kartoved/releases/latest/download/KARTOVED-Portable.zip) · 149 MB | Windows 10/11, 64-bit |

All versions and checksums are in [Releases](https://github.com/ignisdomini/kartoved/releases). The same files are available at [kartoved.ru/app.php](https://kartoved.ru/app.php).

This repository contains release builds and documentation only. The source code is closed — see the [license](LICENSE.md#kartoved-license-agreement).

---

## Android

<p>
<img src="docs/android/01-karta-sputnik.jpg" width="160">
<img src="docs/android/05-sentinel-ndvi.jpg" width="160">
<img src="docs/android/07-gps-kompas.jpg" width="160">
<img src="docs/android/08-pogoda.jpg" width="160">
<img src="docs/android/10-monety.jpg" width="160">
</p>

**Maps**
- Catalogue of historical maps by era and series, search. Download a sheet once and open it in the field without signal.
- Overlay on satellite imagery with adjustable transparency; fine-tune georeferencing with your finger.
- Your own maps: OziExplorer, KMZ/KML, MBTiles, OruxMaps, SQLiteDB. SK-42 sheets are reprojected automatically.
- OpenStreetMap layers: archaeological sites, historic places, heritage protection zones — offline pack for all of Russia.

**Sentinel-2 imagery.** True and false colour, NDVI, NDRE and soil moisture since 2017. Vegetation reveals traces of filled ditches, ramparts, old roads and foundations. Processed on the phone, no keys required.

**Instruments.** GNSS Compass (GPS, GLONASS, Galileo, BeiDou on an astrolabe with a position-quality verdict), 10-day weather with field tips, ARCHEOSCAN, APEX DSP.

**New in 1.5.** Join prospecting organizations (MPR and FPPR) and an offline membership card; find report on the organization's form — PDF, DOC, print, e-mail; finds log with a "Finds" map layer and export to GPX, KML, KMZ, GeoJSON, CSV; place search by name and coordinates; "Forgot password?". Finds and reports stay on your device.

**In the field.** Navigate to a point, track recording with the screen off, waypoints with photos, GPX / KML / KMZ, Russian coins reference, community chat and classifieds.

<details>
<summary>All Android screenshots</summary>

| | | | | |
|---|---|---|---|---|
| ![](docs/android/01-karta-sputnik.jpg) | ![](docs/android/02-karta-prozrachnost.jpg) | ![](docs/android/03-privyazka.jpg) | ![](docs/android/04-svoi-karty.jpg) | ![](docs/android/05-sentinel-ndvi.jpg) |
| ![](docs/android/06-sentinel-panel.jpg) | ![](docs/android/07-gps-kompas.jpg) | ![](docs/android/08-pogoda.jpg) | ![](docs/android/09-pogoda-10-dnej.jpg) | ![](docs/android/10-monety.jpg) |

</details>

## Windows

<p><img src="docs/promo/windows-banner.jpg" width="720"></p>

Everything important from Android on a big screen:
- historical map catalogue, satellite overlay, georeference adjustment;
- **georeferencing module**: place your own image (scan or photo of a map) onto the terrain by control points and save it to .sqlitedb, KML, OruxMaps, Ozi;
- import of third-party maps, Sentinel-2 imagery, weather, ARCHEOSCAN, APEX DSP, sky map;
- waypoints, tracks, gallery, coins reference, chat and classifieds;
- automatic updates.

<details>
<summary>Windows screenshots</summary>

| | |
|---|---|
| ![](docs/windows/slide-1-maps.jpg) | ![](docs/windows/slide-2-layers.jpg) |
| ![](docs/windows/w13-sentinel.jpg) | ![](docs/windows/w13-weather.jpg) |
| ![](docs/windows/w12-import.jpg) | ![](docs/windows/w12-coins.jpg) |
| ![](docs/windows/slide-4-scan.jpg) | ![](docs/windows/w13-apex.jpg) |
| ![](docs/windows/slide-3-sky.jpg) | ![](docs/windows/slide-5-chat.jpg) |

</details>

---

## Installation

**Android.** Download `KARTOVED.apk`, open it on your phone and allow installation from this source. New versions install over previous ones from any official source.

**Windows.** Run `KARTOVED-Setup.exe`. The program is not code-signed yet, so Windows SmartScreen may warn you: "More info" → "Run anyway". Portable: unzip `KARTOVED-Portable.zip` anywhere and run `KARTOVED.exe`.

**Verify.** Each release includes `SHA256SUMS.txt`. Android signing certificate: `CN=KARTOVED`, SHA-1 `f5:af:f3:42:0c:06:81:4f:d5:c9:f9:f6:ef:d0:be:2d:e9:e7:a4:0f`.

**Android updates without a store** — via [Obtainium](https://github.com/ImranR98/Obtainium): add `https://github.com/ignisdomini/kartoved`.

## Account

Registration is free — in the app or at [kartoved.ru](https://kartoved.ru/register.php). Without signing in only the satellite map is available.

## Privacy

Waypoints, tracks and your own maps stay on the device. For the weather forecast, coordinates are rounded to a ~5 km cell. No ads, no third-party analytics.
[Privacy policy (RU)](https://kartoved.ru/privacy.php) · [account deletion](https://kartoved.ru/account.php#delete)

The app is a tool for historians and local researchers. Excavation without an official permit is prohibited by Russian law.

## Contact

Andrey Apostol · apostolgroup@gmail.com · [kartoved.ru](https://kartoved.ru) · [Issues](https://github.com/ignisdomini/kartoved/issues)

---

© 2006–2026 KARTOVED Project. All rights reserved. Free license for use only — [LICENSE.md](LICENSE.md#kartoved-license-agreement).
Data: © OpenStreetMap contributors (ODbL) · Contains modified Copernicus Sentinel data · weather by Open-Meteo (CC BY 4.0) · Esri basemap.
