---
title: '2020.1128'
date: 2020-11-28
---

## Achievement
![](res/lyric-import.png)
- Implement lyric importer to handle a list of steps need user to do in order.

## Code quality
- Clean-up code. [karaoke](#243@andy840119)

## Beatmap
- Create `TimeTagsConverter` to support to encode/decode time-tag with json format. [karaoke](#244@andy840119)
- Add `language id` in lyric object do define which laguage lyric is. [karaoke](#261@andy840119)

## Editor
- Implement lyric importer.
  - Base implementation. [karaoke](#250@andy840119)
  - Implement drag screen in lyric import. [karaoke](#257@andy840119)
  - Add lyric editor's step two. [karaoke](#262@andy840119)
- Implement time tag tooltip. [karaoke](#254@andy840119)
- Create circle singer avatar, [karaoke](#255@andy840119)
- Base definition `LyricEditor`'s edit mode. [karaoke](#260@andy840119)

## Tooling
- Implement time tag utility to make the conversion and invalid time-tag checking. [karaoke](#246@andy840119)
- Implement `Japanese lyric` time tag generator. [karaoke](#251@andy840119)
- Implement `Japanese lyric` ruby generator. [karaoke](#252@andy840119)
- Implement Implement auto-detect lyric's language. [karaoke](#264@andy840119)