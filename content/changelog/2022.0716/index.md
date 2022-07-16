---
title: '2022.0716'
date: 2022-07-16
---

## Achievement
- Finall got that cool M1 macbook.
- Waiting for that stupid laptop for 3 months.

## Code quality
- Enable NRT in the skinning. [karaoke](#1412@andy840119)
- Use `IList<T>` instead of `List<T>` in the karaoke beatmap. [karaoke](#1410#1413@andy840119)
- Remove null check in the caret algorithm. [karaoke](#1414@andy840119)
- Fix null assign in the lyric text. [karaoke](#1415@andy840119)
- Use `string.Empty` instead of `""`. [karaoke](#1416@andy840119)
- Enable NRT in the extensions. [karaoke](#1418@andy840119)
- Enable NRT in the change handler. [karaoke](#1419@andy840119)
- Enable NRT in the json serializer. [karaoke](#1421@andy840119)
- Enable NRT in the lyric editor state. [karaoke](#1423@andy840119)
- Remove nullable disable annotation in the asserts utils. [karaoke](#1427@andy840119)
- Clean-up some bad code. [karaoke](#1428@andy840119)
- Move the `<Nullable>enable</Nullable>` into props file. [karaoke](#1430@andy840119)
- Remove nullable disable annotation in the test project. [karaoke](#1431@andy840119)
- Refactor the interface in the lyric selection button. [karaoke](#1434@andy840119)

## Fix
- Use temp way to fix font might not appear if using nvidia graphic card. [karaoke](#1318#1426@andy840119)
- Fix should not call the change handler if not edit the text in the lyric editor. [karaoke](#1437@andy840119)
- Fix will cause crash if switch from translate screen to singer screen. [karaoke](#1436#1438@andy840119)

## Tooling
- [Close duplicated] Make a CI for checking if user generated the localization resource file. [karaoke](#1269@andy840119)

## UI/UX
- Adjust the ` lyric selection` style in the lyric editor. [karaoke](#1433@andy840119)