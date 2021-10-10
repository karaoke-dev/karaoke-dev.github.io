---
title: '2021.0509'
date: 2021-05-09
---

## Achievement
- \56 stars in repo/

## Code quality
- Remove singer property in note object. This property can get from parent lyrics directly. [karaoke](#574@andy840119)
- Rename `EditRuleset` and `EditPlayfield` to use the full `Editor` keyword, follow how official do. [karaoke](#579#583@andy840119)
- Separate `note playfield` for letting code be more re-usable. [karaoke](#584@andy840119)
- Clean up code. [karaoke](#586@andy840119)

## Editor
- Implement check some property in lyric. [karaoke](#572@andy840119)
- Implement note checker. [karaoke](#573@andy840119)
- Implement overlay in lyric editor. [karaoke](#577@andy840119)
- Base implement edit note overlay. [karaoke](#580@andy840119)
- Implement `time-tag` timing editor. [karaoke](#595#596#597#598#599@andy840119)
  ![](res/time-tag-time-editor.png)

## Fix
- Fix switch back to view note will cause errors in the lyric editor. [karaoke](#576@andy840119)
- Fix not display lyrics in the singer editor. [karaoke](#602@andy840119)

## Gameplay
- Make `lyric` / `note` playfield transparent can be adjusted. [karaoke](#561#570@andy840119)
- Adjust overally lyric scale instead of adjust main lyric size(might cause size messy issue). [karaoke](#559#571@andy840119)

## Skinning
- Sync skin component. [karaoke](#587@andy840119)

## Tooling
- Use lazy way to fix deploy service not working. [karaoke](#600@andy840119)