---
title: "2022.0625"
date: 2022-06-25
---

## Achievement

- Sepatate resource into individual repo for better management.
- Adjust the `CI` for auto upload the new translation into `crowdin`.
- Waiting for new macbook for almost 3 monthes and got nothing.
- Make the upgrade to my cool keyboard.

## Code quality

- Use more generic way to change the value to the input area in the editor. [karaoke](#1379@andy840119)
- Implement test case for `beatmap change handler`. [karaoke](#1386@andy840119)
- Create test case for remain change handler. [karaoke](#1389@andy840119)
- Rename from `Saiten` to `Scoring` for better understanding. [karaoke](#1391#1392@andy840119)
- Enable NRT(`nullable reference types`, or called `寢取られ` in the Japanese) by default. [karaoke](#1394@andy840119)
  - Enable NRT in the `caret position` and c`alculation algorithm`. [karaoke](#1395@andy840119)
  - Enable NRT in the `mods`. [karaoke](#1397@andy840119)
  - Enable NRT in the `editor checks`. [karaoke](#1398@andy840119)
  - Enable NRT in the `lyric property generator`. [karaoke](#1399@andy840119)
  - Enable NRT in the `localisation namespace`. [karaoke](#1400@andy840119)
  - Enable NRT in the `configuration`. [karaoke](#1401@andy840119)
  - Enable NRT in the `beatmap`. [karaoke](#1402@andy840119)
  - Enable NRT in `some parts`. [karaoke](#1403@andy840119)
  - Enable NRT in the `bindable`. [karaoke](#1404@andy840119)
  - Enable NRT in the `replays`. [karaoke](#1405@andy840119)
  - Enable NRT in the `hit objects`. [karaoke](#1406@andy840119)
  - Enable NRT in the `difficulty`. [karaoke](#1407@andy840119)
  - Enable NRT in the `utils`. [karaoke](#1408@andy840119)
  - Enable NRT in the `test case helper`. [karaoke](#1409@andy840119)

## Editor

- Able to upload the `avatar` to the `singer` in the editor. [karaoke](#1377#1380@andy840119)
  ![](res/2022-06-25-21-45-07.png)
- Should be able to show the `singer avatar` in the tooltip. [karaoke](#1381#1382@andy840119)

## Framework

- Enable NRT in the font package. [font-package](#223@andy840119)
- Enable NRT in the microphone package. [microphone-package](#245@andy840119)

## Fix

- Should update singer info in the tooltip after singer info updated. [karaoke](#1372#1373@andy840119)
- Fix the invalid singer size issue in the lyric editor. [karaoke](#1371#1374@andy840119)

## Localization

- Make the `section title` become able to be translate in the editor. [karaoke](#1383@andy840119)
- Make `selection button` become able to be translate in the editor. [karaoke](#1384@andy840119)

## Resources

- Moving the `resource file` into another dll. [karaoke](#1366#1367@andy840119)

## Setting

- Implement `first-run step` for the ruleset. [karaoke](#1362#1376@andy840119)

## Tooling

- [outdated] Add github action for upload the localisation to crowdin. [karaoke](#1368#1369#1370@andy840119)
