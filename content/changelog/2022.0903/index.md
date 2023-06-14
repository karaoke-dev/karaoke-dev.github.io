---
title: "2022.0903"
date: 2022-09-03
---

## Achievement

- Back to the office.
- Upgrade the csharp language to the latest.
- Airpods missing again ;\_;
- Start implement strategy to sync the lyric property from another lyric, will use for those repeating lyrics.
- Got that stupid RTX 3090

## Beatmap

- Implement reference lyric strategy class. [karaoke](#1523@andy840119)
- Implement strategy to sync the value from reference lyric. [karaoke](#1537#1467#1538@andy840119)

## Code quality

- Implement base property seciotn for those hit-object proerty related edit area. [karaoke](#1515#1516@andy840119)
- Implement Implement generic type convertor for able to deal with field with interface. [karaoke](#1520@andy840119)
- Make karaoke skin element convertor inherit generic convertor. [karaoke](#1521@andy840119)
- Make sure that deep clone the lyric will also copy the reference config. [karaoke](#1525@andy840119)
- Unify the text usage in the lyric editor section. [karaoke](#1526#1531@andy840119)
- Refactor perform on selection. [karaoke](#1549@andy840119)
- Separate note property change handler into individual class. [karaoke](#1551@andy840119)
- Small refactor the code in the change handler. [karaoke](#1552@andy840119)

## Editor

- Implement select reference lyric popover. [karaoke](#1517@andy840119)
- Able to assign the reference lyric in the right side section. [karaoke](#1488#1528@andy840119)
  ![](res/2022-09-03-19-53-23.png)
- Block some property change in the change handler. [karaoke](#1534@andy840119)
- Should not save some property in the note if has reference lyric config. [karaoke](#1533#1535@andy840119)

## Framework

- Upgrade to latest font framework to support more frame-buffer layer. [karaoke](#1507@andy840119)

## Fix

- Add missing DI and should call the change handler after reference lyric changed. [karaoke](#1518@andy840119)
- Fix re-binding config cause error in the reference lyric section. [karaoke](#1527#1529@andy840119)
- Handle different network related exceptions in the karaoke changelog. [karaoke](#1509#1532@andy840119)

## Utility

- Create utils for finding hitobject in the editor beatmap. [karaoke](#1544@andy840119)
- Add utils to check if the field is editable in the utils or config. [karaoke](#1547#1548@andy840119)
