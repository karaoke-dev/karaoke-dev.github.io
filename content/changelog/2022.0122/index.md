---
title: "2022.0122"
date: 2022-01-22
---

## Achievement

- \Hit 100 stars/

![](res/2022-01-22-09-44-49.png)

## Beatmap

- Check is there any reason why not use `bindable list` for tags in lyric. [karaoke](#1028@andy840119)
- Make `TimeTag[]` TimeTags into `IEnumerable<TimeTag>` in the lyric class. [karaoke](#1027@andy840119)
- Change some properties from `Bindable<tag[]>` into `BindableList<tag>` in lyric. [karaoke](#1031@andy840119)

## Code quality

- `int shifting` should be renamed to `int offset` in some methods. [karaoke](#1033#1035@andy840119)

## Fix

- Fix screen broken after add new text in lyric editor. [karaoke](#1005@andy840119)
- Fix cause crash if change mode after delete the lyric. [karaoke](#1008@andy840119)
- Fix the `lyric importer` will crash if switch mode in edit lyric mode. [karaoke](#1012#1013@andy840119)
- Fix import test scene does not have `popover screen`. [karaoke](#1007#1014@andy840119)
- Fix `auto-generate` not working if trigger open the selecting mode by not in the generating mode. [karaoke](#1020@andy840119)
- Fix `time-tag` is not in the right place in the lyric importer. [karaoke](#1018#1022@andy840119)
- Fix `delete text tag` not wrap into `change handler` in text tag edit selection. [karaoke](#1029#1032@andy840119)
- Fix `ruby`/`romaji` cannot drag in lyric editor. [karaoke](#1024#1034@andy840119)
- Fix some UI bug in singer editor page. [karaoke](#1043@andy840119)
- Fix `multi select` not working in singer editor. [karaoke](#1048@andy840119)
- Fix something might broken in the `translate editor`. [karaoke](#1049#1051@andy840119)

## Editor

- Implement typing feature in lyric editor. [karaoke](#1003@andy840119)
- Should use `change handler` if change text-tag properties. [karaoke](#1009@andy840119)
- move more `caret position calculation` algorithm into caret state class. [karaoke](#1011@andy840119)
- Apply auto generator config in change handler. [karaoke](#1016@andy840119)
- Refactor navigation bar and lyric editor screen in lyric importer. [karaoke](#1017@andy840119)
- After click auto generate language dialog, should select all language in lyric importer. [karaoke](#994@andy840119)
- Fix navigation bar in lyric importer not change text in some cases. [karaoke](#1019@andy840119)
- Implement extend state class for able to record status in lyric editor. [karaoke](#1021@andy840119)
- Implement delete range of ruby romaji in lyric editor. [karaoke](#1026@andy840119)
- Implement update singer list in lyric editor extend area if change in the beatmap. [karaoke](#1037@andy840119)
- Implement singer selection in lyric editor. [karaoke](#1040@andy840119)
- Adjust edit singer style in lyric editor. [karaoke](#1044@andy840119)
- Should use `change handler` in singer list page if `assign` or `un-assign` singer to lyric.

![](res/2022-01-22-09-18-49.png)
