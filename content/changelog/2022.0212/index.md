---
title: "2022.0212"
date: 2022-02-12
---

## Achievement

- \No 1111 has been created/ [karaoke](#1111@andy840119)
- Close lots of old issues.
- Create and close lots of new issues.
- Write this damn article.
- Migrate skin roles for more flexibility.

## Beatmap

- Add primary key into lyric object. [karaoke](#1078@andy840119)
- Record HUE instead of Hex in the singer(for not let user to select the dirty color). [karaoke](#1042@andy840119)
- Remove all layout index in the lyric. [karaoke](#1079#1089#1090#1091#1092#1093@andy840119)
- [outdated] Change `ruby`/`romaji` from `bindable` to `bindable list` in the lyric object. [karaoke](#891@andy840119)

## Code quality

- Use the better way for able to access editor in test scene.
- Fix Assert.AreEqual wrong using. [karaoke](#1100#1111@andy840119)

## Editor

- Should wrap change handler in note popover. [karaoke](#1053#1055@andy840119)
- Should wrap change in `importLyric` method in `KaraokeEditor`. [karaoke](#1054#1056@andy840119)
- Combine notes and note property into single change handler. [karaoke](#1058#1059@andy840119)
- Adjust style in translate editor. [karaoke](#1060@andy840119)
- Fix some issue in singer editor and tooltip. [karaoke](#1062@andy840119)
- Separate karaoke beatmap skin from karaoke skin. [karaoke](#1065@andy840119)
- Refactor caret position algorithm interface. Use better interface instead of call method be reflection. [karaoke](#1074@andy840119)
- Editor screen should have its own editor click for able to control the track time. [karaoke](#1104#1106@andy840119)
- [outdated] Make some improvement about lyric editor. [karaoke](#960@andy840119)
- [outdated] Implement input feature in lyric edit mode. [karaoke](#958@andy840119)
- [outdated] Improve lyric importor. [karaoke](#731@andy840119)
- [outdated] Should deal with the case if singer name is tooooooo long. [karaoke](#773@andy840119)
- [outdated] Should have config button in auto-generate area. [karaoke](#759@andy840119)
- [outdated] Create generate manager. [karaoke](#730@andy840119)
- [outdated] Implement typing feature in lyric editor. [karaoke](#668@andy840119)
- [outdated] Fix typing caret position is weird. [karaoke](#664@andy840119)
- [outdated] Fix non-english text input. [karaoke](#504@andy840119)
- [outdated] Implement note auto-generator. [karaoke](#501@andy840119)
- [outdated] Should add textbox to handle input in text edit mode. [karaoke](#487@andy840119)
- [outdated] Able to get the config directly in lyric editor. [karaoke](#476@andy840119)
- [outdated] Make shadow offset smaller in lyric editor. [karaoke](#351@andy840119)
- [outdated] Implement singer editor. [karaoke](#214@andy840119)

## Fix

- Make the ruleset able to read customized beatmap. [karaoke](#1087@andy840119)
- Seems internal skin is not loaded well in release build. [karaoke](#1100@andy840119)
- Fix the issue that cannot enter the editor. [karaoke](#1103@andy840119)
- Invest the reason why cannot enter the editor in release lezer. [karaoke](#1102@andy840119)
- Fix internal skin is not loaded well in release build. [karaoke](#1099@andy840119)
- [outdated] Fix lyric font broken if playback. [karaoke](#772@andy840119)

## Setting

- Should be able to show the release version someplace. [karaoke](#1101#1112@andy840119)

## Skinning

- Adjust folder structure and add class for new skin structure. [karaoke](#1075@andy840119)
- Apply new skin structure into karaoke beatmap. [karaoke](#1076@andy840119)
- Apply new skin roles in the karaoke beatmap. [karaoke](#1077@andy840119)
- Migrate to the new skin formats. [karaoke](#1080@andy840119)
- Should have default beatmap if from legacy skin. [karaoke](#1083@andy840119)
- Have ApplyTo() function in the skin element for able to adjust skin effect by the skin element. [karaoke](#1081#1084@andy840119)
- Remove continuous property in lyric layout. [karaoke](#1089@andy840119)
- [outdated] Refactor layout structor in karaoke skin. [karaoke](#901@andy840119)
