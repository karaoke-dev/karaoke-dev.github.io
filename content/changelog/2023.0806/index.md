---
title: "2023.0806"
date: 2023-08-06
---

## Achievement

- Trying to move the romaji text into the time-tag.

## Beatmap

- Should change the id after `DeepClone()` the lyric. [karaoke](#2054@andy840119)
- [outdated] Use Grid instead of int as primary key. [karaoke](#2040@andy840119)
- Add romaji text into time tag. [karaoke](#2070@andy840119)

## Code quality

- [outdated] Remove all `AllowNull` using. [karaoke](#1511@andy840119)
- [outdated] Remove all #nullable disabled annotation. [karaoke](#1986@andy840119)
- Remove nullable disable annotation in the graphic namespace. [karaoke](#2064@andy840119)
- Close `Enable NRT by default` issue because most part of class already removed nullable disable annotation. [karaoke](#1390@andy840119)
- Create `dotnet-format.yml` for able to check the file format(but it's still not working ;\_;). [karaoke](#2065@andy840119)
- Sync the dotnet setting from osu project. [karaoke](#2066@andy840119)
- (Finally) Normalise trailing commas in code. [karaoke](#991#2067@andy840119)
- [outdated] Move some utils to the `Objects` namespace. `Utils` in the root namespace should be global enough, like `processing the enum`. [karaoke](#1206@andy840119)
- [outdated] Use `EqualityComparer<CultureInfo>.Default` to compare the language. [karaoke](#1117@andy840119)
- Regular clean up code. [karaoke](#2068@andy840119)
- Refactor the test case helper for able to re-use the regex. [karaoke](#2073@andy840119)
- Use `<br/>` to change new line in the comment. [karaoke](#2072#2074@andy840119)
- Refactor the test case for testing the `generator` in the `change handler`. [karaoke](#2080@andy840119)
- Use better way to catch exception in the `test case assertion`. [karaoke](#2081@andy840119)
- Remove `generate type` property in the `caret position`. We already got the better way to check if the caret is move by `mouse` or `keyboard`. [karaoke](#2082@andy840119)
  - Remove the override function in the caret position algorithm test because it can use object equality check instead. [karaoke](#2083@andy840119)
  - Make the test case method static. [karaoke](#2085@andy840119)
- Create `ActivatorUtils` for able to create the utility with target type. [karaoke](#2086@andy840119)

## Editor

- [outdated] Implement issue table in the lyric editor composer. [karaoke](#1728@andy840119)
- Add more cases for handle the `ruby text` in the `time-tag tag helper`. [karaoke](#2076@andy840119)
- Implement the `romaji generator` for fill the property inside the `time-tag`. [karaoke](#2077@andy840119)
  - Change romaji generator return type from array to the dictionaty. [karaoke](#2078@andy840119)
- Add method in the `change handler` for able to change the `romaji text` and the `initial state` in the `time-tag`. [karaoke](#2079@andy840119)

## Gameplay

- [outdated] Fix lyric display issue. [karaoke](#1641@andy840119)
- Create `Gameplay is not working.` issue due to mis-understanding. [karaoke](#2071@andy840119)
