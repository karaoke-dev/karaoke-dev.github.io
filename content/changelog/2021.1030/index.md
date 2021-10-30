---
title: '2021.1030'
date: 2021-10-30
---

## Achievement
- Fix some outline performance issue, big thanks to [@Evast](https://github.com/EVAST9919)
- Buy an M32Q monitor.

## Editor
- Fix `time-tag` position is wrong in `editor`. [karaoke](#869@andy840119)

## Framework
- Fix `frame-buffer` performance issue. [font-package](#65@andy840119)
- Implement get shader instance directly by extension and adjust test case usage. [font-package](#66@andy840119)
- Fix `outline shader` performance issue. [font-package](#68@EVAST9919)
- Implement `pixel shader`. [font-package](#55#69@andy840119)
- Make `internal shader` has its own class. [font-package](#70@andy840119)
- Implement repeat moving background effect. [font-package](#72@andy840119)
- Clean-up code. [font-package](#73@andy840119)

## Gameplay
- Move `SettingHUDOverlay` into `HUDOverlay`. [karaoke](#862#863@andy840119)
- Fix some weird behavior in `setting config button`. [karaoke](#864@andy840119)
- Fix practice mode broken. [karaoke](#868@andy840119)
- Fix outline text cause performance issue. [karaoke](#871@andy840119)
- Config section should be on the left side if the config button is on the left side. [karaoke](#873#876@andy840119)
  ![](res/2021-10-30-09-32-20.png)
- Adjust config style in gameplay by following the config style. [karaoke](#872#877@andy840119)

## Setting
- Should update button style by following new `setting overlay design`. [karaoke](#867@andy840119)

## Testing
- Fix import lyric test case broken. [karaoke](#878#879@andy840119)