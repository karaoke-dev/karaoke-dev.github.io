---
title: '2021.0918'
date: 2021-09-18
---

## Achievement
- Nope i guess.

## Code quality
- Clean up code. [karaoke](#822@andy840119)
- Adjust project format like `osu.Game` project. [karaoke](#823@andy840119)
- Move `karaokeIcon.cs` file into sprite namespace. [karaoke](#827@andy840119)
- Upgrade syntax to `C# 9`. [karaoke](#829@andy840119)
- Clean up code again to meet the coding style of `C# 9`. [karaoke](#830@andy840119)

## Editor
- Fix the case that some of editor component is not visible in test case. [karaoke](#837#838@andy840119)
- Implement base karaoke setup section. [karaoke](#841@andy840119)
- Add singer section in singer in setup screen. [karaoke](#842@andy840119)

## Fix
- Fix singer description now showing in tooltip. [karaoke](#843@andy840119)
- Update package and fix api change error. [karaoke](#844@andy840119)
- Fix cannot show `changelog` and `dialogs` after upgrade to the latest package. [karaoke](#845#846@andy840119)

## Reliability
- Fix got error if first open `setting overlay`. [karaoke](#819#820@andy840119)
- Upgrade microphone package to prevent crash when access microphone device. [karaoke](#826@andy840119)

## Setting
- Fix cannot enter `config page`. [karaoke](#814@andy840119)
- Fix the case user cannot press exit button to exit `config page`. [karaoke](#825@andy840119)
- Should show `default` instead of `no microphone device` if use default microphone device in config page. [karaoke](#828#835@andy840119)

## Framework
- Add `github action` to run `CI` if create new PR. [karaoke-microphone](#45@andy840119)
- Add `github action` to run `CD` for create package if create new tag. [karaoke-microphone](#49@andy840119)
- Fix microphone crash issue after upgrade to latest o!f. [karaoke-microphone](#50@andy840119)
- Refactor code in microphone package. [karaoke-microphone](#52@andy840119)
- Should use name `decibel` instead of `loudness`. [karaoke-microphone](#55@andy840119)
- Should set pitch as zero is decibel is toooo small. [karaoke-microphone](#56@andy840119)
- Fix api change in `font package` while updating the pacakge. [font-package](#37@andy840119)