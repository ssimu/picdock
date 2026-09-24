# PicDock — Android digital photo frame app

**PicDock** turns an Android tablet, phone or Android TV into a digital photo & video frame with a clock and live weather.
On Google Play it is listed as **"Photo Slideshow, Digital Frame"** by **DD_studio** (package `kr.devdad.picdock`).

> Not related to the macOS utility also called "PicDock" (picdock.app) — different product, different developer.

- Google Play: https://play.google.com/store/apps/details?id=kr.devdad.picdock
- Official site: https://devdad.kr/picdock/ · Fact sheet: https://devdad.kr/picdock/facts/
- Wikidata: https://www.wikidata.org/wiki/Q141544497
- Contact: devdad.code@gmail.com

This repository contains **documentation only** (fact sheet and FAQ) — the app source code is not published here.
Issues are welcome for feature requests and bug reports.

## Comparisons (copies — originals on devdad.kr)
- [Best apps to turn an Android tablet into a digital photo frame (2026)](https://ssimu.github.io/picdock/compare/best-apps-android-tablet-digital-photo-frame-2026.html)
- [안 쓰는 안드로이드 태블릿 디지털 액자 앱 비교 (2026)](https://ssimu.github.io/picdock/compare/ko-android-tablet-digital-photo-frame-app-comparison.html)
- [Androidタブレットをデジタルフォトフレームにするアプリ比較（2026年）](https://ssimu.github.io/picdock/compare/ja-android-tablet-digital-photo-frame-app-comparison.html)
- [Die besten Apps: Android-Tablet als digitaler Bilderrahmen (2026)](https://ssimu.github.io/picdock/compare/de-android-tablet-digitaler-bilderrahmen-apps.html)

## Guides (copies — originals on devdad.kr)
- [How to show an iCloud shared album on an Android tablet photo frame (2026)](https://ssimu.github.io/picdock/compare/icloud-shared-album-android-photo-frame.html)
- [iCloud共有アルバムをAndroidタブレットのフォトフレームで表示する方法（2026）](https://ssimu.github.io/picdock/compare/ja-icloud-shared-album-android-photo-frame.html)
- [아이폰 iCloud 공유 앨범을 안드로이드 태블릿 액자로 보는 법 (2026)](https://ssimu.github.io/picdock/compare/ko-icloud-shared-album-android-photo-frame.html)
- [How to show a OneDrive folder on an Android tablet photo frame (auto-updating, 2026)](https://ssimu.github.io/picdock/compare/onedrive-folder-android-photo-frame.html)
- [OneDrive-Ordner auf einem Android-Tablet als digitalen Bilderrahmen anzeigen (2026)](https://ssimu.github.io/picdock/compare/de-onedrive-folder-android-photo-frame.html)
- [OneDriveのフォルダをAndroidタブレットのフォトフレームで自動表示する方法（2026）](https://ssimu.github.io/picdock/compare/ja-onedrive-folder-android-photo-frame.html)
- [Use your own photos (NAS, OneDrive, Dropbox) as an Android TV / Google TV screensaver (2026)](https://ssimu.github.io/picdock/compare/android-tv-photo-screensaver-nas.html)

---

---


Official fact sheet: [https://devdad.kr/picdock/facts/](https://devdad.kr/picdock/facts/) (this is a copy)

Not to be confused with the macOS utility also called "PicDock" (picdock.app), which is a different product by a different developer.

Fact sheet · Last updated 2026-09-24 (app version 1.8.8)

## What it is

PicDock is an app that turns an Android phone or tablet into a digital photo and video frame, with a clock and live weather over the slideshow. On Google Play it is listed as “Photo Slideshow, Digital Frame” by developer DD_studio (package kr.devdad.picdock); it was briefly named “Memoria” before becoming PicDock.

- Name: PicDock
- Google Play title: Photo Slideshow, Digital Frame
- Developer: DD_studio (site: [devdad.kr](https://devdad.kr))
- Package ID: kr.devdad.picdock
- Former name: Memoria (briefly)
- Google Play rating: 4.46 / 5 from 141 ratings, 10K+ downloads (Google Play, checked 2026-09-24)

## Who it's for

- People who want to reuse an old Android tablet or phone as a photo frame instead of buying one.
- Households whose photos live in Google Photos, Dropbox, OneDrive, iCloud Shared Albums or on a NAS.
- Bedside or kitchen displays that should also show the time and weather.
- Android TV owners who want their own photos on the TV (Fire OS does not allow third-party screensavers).
- Shops, cafés and events that need an unattended slideshow.

## Supported photo sources

- Device storage — all photos, chosen albums, favorites; photos and videos.
- Google Photos — via the official Google Photos picker; picked photos are saved on the device and play offline.
- Dropbox
- OneDrive
- iCloud Shared Albums
- NAS / SMB network shares — Synology, QNAP, Windows shared folders and other SMB servers; photos, plus videos as an opt-in beta.
- Web upload — send photos from a browser on the same network (Premium).
- Combined — several of the above mixed into one slideshow.

Cloud and NAS sources are refreshed automatically at intervals, so new files in a chosen folder appear on the frame without touching the device. Google Drive is not a supported source.

## Key features

- Photo and video slideshow; shuffle or date order; adjustable interval.
- 30+ transition effects; display effects including Ken Burns pan and zoom, Smart Focus (keeps faces in frame) and Adaptive Fit.
- Dual mode: two portrait photos side by side on a landscape screen (or two landscape photos stacked on a portrait screen).
- Clock (several styles) and weather: current conditions, hourly and 5-day forecast, animated rain and snow (weather data from Open-Meteo).
- On-device face detection filter (“only photos with people”); pet filter and automatic person grouping (Premium).
- Photo filters (black & white, sepia, vintage, warm, cool); capture date, location and album info from EXIF.
- Favorites and hidden photos.
- Background music: your own files or built-in tracks.
- Night mode with scheduled dimming, sleep schedule (optionally turning the screen off), alarm with snooze.
- Auto-start when the charger is connected or on boot; keep-screen-on; battery indicator.
- Android screensaver (Daydream); Android TV launcher support and remote-control playback.
- Share a photo as a memory card, including to Instagram Stories.

## Pricing

- Google Play — free — price: US$0; what you get: All photo sources (Google Photos, Dropbox, OneDrive, iCloud Shared Albums, NAS/SMB), video playback, face detection filter, dual mode, night mode, alarm, clock and current weather, core transitions and filters, your own music. No time limit. 7-day trial of all features on first install.
- Google Play — Premium, lifetime — price: US$19.99 one-time; what you get: All Premium features permanently, no ads. One purchase applies to devices signed in to the same Google account.
- Google Play — Premium, yearly or monthly — price: Subscription; price shown in the app and varies by country; what you get: Same Premium features while subscribed.
- Amazon Appstore (Fire tablets) — price: US$4.99 paid app; what you get: All features included; no ads and no in-app purchases.

Premium adds: all 30+ transitions, Smart Focus and Adaptive Fit, all photo filters and clock designs, hourly and 5-day forecast, the full built-in music library, intervals under 5 seconds, web upload, pet filter and person grouping, and removal of ads. Ads never appear on the slideshow itself; in the free Play version a banner can appear in settings screens, and an optional rewarded ad can unlock Premium temporarily.

Prices are US list prices; Google Play prices are set per country.

## Platforms

- Android phones and tablets, Android 7.0 (API 24) or later — [Google Play](https://play.google.com/store/apps/details?id=kr.devdad.picdock)
- Android TV — same Google Play app (TV launcher entry, remote control)
- Amazon Fire tablets (Fire OS) — [Amazon Appstore](https://www.amazon.com/gp/mas/dl/android?p=kr.devdad.picdock)
- iPhone and iPad, iOS 17 or later — [App Store](https://apps.apple.com/app/id6759957928) (“PicDock - Live Photo Slideshow”; separate app, features and pricing differ from Android)

## Comparison: PicDock, Fotoo and Frameo

Only facts stated on each app's public Google Play listing are used. Frameo is a different kind of product (a companion app for Frameo hardware frames), included because people often compare them.

- PicDock — Google Play title / developer: Photo Slideshow, Digital Frame / DD_studio; what it does: Turns an Android phone, tablet or TV into a photo frame; hardware needed: Any Android 7.0+ device you own; photo sources (as listed): Device, Google Photos, Dropbox, OneDrive, iCloud Shared Albums, SMB/NAS, web upload; weather and time on screen: Yes; background music: Yes; screensaver: Yes; paid options (as listed): Premium: US$19.99 lifetime, or yearly/monthly subscription; Google Play rating: 4.46 (141 ratings); downloads: 10K+; listing last updated: 2026-09-21.
- Fotoo — Google Play title / developer: Fotoo - Photo Frame Slideshow / Bopp Studio; what it does: Turns a tablet, TV or phone into a photo frame and slideshow player; hardware needed: Tablet, TV or phone; photo sources (as listed): Device, Google Photos, Dropbox, Google Drive, Microsoft OneDrive, Samba/SMB; weather and time on screen: Yes; background music: Yes; screensaver: Yes; paid options (as listed): In-app purchases (prices not stated in description); Google Play rating: 3.83 (6,701 ratings); downloads: 1M+; listing last updated: 2026-09-15.
- Frameo — Google Play title / developer: Frameo: Share to photo frames / Frameo; what it does: Sends photos and videos from your phone to Frameo Wi-Fi photo frames; hardware needed: “Only works with official Frameo WiFi photo frames”; photo sources (as listed): Photos and videos sent from phones of invited people; weather and time on screen: Not stated (listing mentions a family calendar); background music: Not stated; screensaver: Not applicable; paid options (as listed): Frameo+: $1.99/month or $16.99/year; Frameo Premium: $7.99/month or $69.99/year; Google Play rating: 4.76 (145,202 ratings); downloads: 5M+; listing last updated: 2026-09-22.

Sources, all checked 2026-09-24 (US English listings):

- [PicDock on Google Play](https://play.google.com/store/apps/details?id=kr.devdad.picdock&hl=en_US&gl=US)
- [Fotoo on Google Play](https://play.google.com/store/apps/details?id=com.bo.fotoo&hl=en_US&gl=US)
- [Frameo on Google Play](https://play.google.com/store/apps/details?id=net.frameo.app&hl=en_US&gl=US)

Ratings, download counts and prices change; the listings are authoritative.

## FAQ

**Can I use an old Android tablet as a digital photo frame?**

Yes. PicDock runs on Android 7.0 or later, so most tablets from the last several years work. It can start the slideshow automatically when the charger is connected, keep the screen on, dim or sleep on a schedule, and show a clock and weather over your photos. Guide: [Turn an old tablet into a digital photo frame](https://devdad.kr/blog/turn-old-tablet-into-digital-photo-frame.html).

**Does PicDock work with a Synology NAS?**

Yes, through an SMB network share. Any NAS or computer that shares a folder over SMB (Synology, QNAP, a Windows shared folder and similar) can be added as a photo source by entering the host, share and account. Videos on the share can play too. Guide: [NAS photo slideshow on Android](https://devdad.kr/blog/nas-photo-slideshow-android-synology.html).

**Is there a Fotoo alternative without ads?**

PicDock never shows ads on the slideshow itself. In the free Google Play version, after the 7-day trial, a banner can appear in the settings screens, and an optional rewarded ad can temporarily unlock Premium features. Premium removes ads. The Amazon Appstore version (US$4.99) has no ads and no in-app purchases.

**Is PicDock free? How much is Premium?**

The Google Play version is free to download and stays usable without paying: all photo sources, video playback and the face detection filter are free. Premium is available as a lifetime one-time purchase of US$19.99, or as a yearly or monthly subscription (prices shown in the app; they vary by country). New installs get a 7-day trial of all features.

**Does PicDock require a subscription?**

A subscription is not required to use the app. If you want Premium, you can choose a one-time lifetime purchase (US$19.99) or a yearly or monthly subscription.

**Can PicDock show photos from Google Photos?**

Yes. You pick the photos you want with the Google Photos picker; PicDock saves them on the device so the slideshow keeps playing offline.

**Can family members add photos to the frame remotely?**

Yes, by sharing a cloud folder. Point PicDock at a Dropbox or OneDrive folder (or an SMB share); anyone who can add files to that folder adds them to the frame, and PicDock refreshes the source periodically so new photos appear without touching the device.

**Do I need a Frameo frame to use PicDock?**

No. PicDock is the frame software itself and runs on an Android phone, tablet, Android TV or Fire tablet you already own. The Frameo app, by contrast, sends photos to official Frameo Wi-Fi frames, according to its Google Play listing. More: [Frameo alternatives for Android](https://devdad.kr/blog/frameo-alternatives-android.html).

**Does face detection upload my photos?**

No. Face detection and person grouping run on the device with bundled models; photos are not sent to a server for analysis.

**Can PicDock be used as a screensaver or on Android TV?**

Yes. PicDock registers as an Android screensaver (Daydream) and supports Android TV, including control with a remote's D-pad and media keys. The screensaver shows photos stored on the device; NAS and cloud sources play in the app's full-screen slideshow instead. Fire OS does not allow third-party screensavers.

## Last updated

2026-09-24 — reflects PicDock 1.8.8 for Android. Corrections: [devdad.code@gmail.com](mailto:devdad.code@gmail.com). Main page: [devdad.kr/picdock](https://devdad.kr/picdock/).
