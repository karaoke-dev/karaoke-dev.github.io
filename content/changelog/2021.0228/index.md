---
title: '2021.0228'
date: 2021-02-28
---

## Code quality
- Move some tooltips out of Graphics/Cursor namespace. [karaoke](#470@andy840119)
- Re-write `TimeTagsUtilsTest` test. [karaoke](#477@andy840119)
- Combine `LyricEditor` and `LyricEditorStateManager`. [karaoke](#489@andy840119)
- Refactor cursor position algorithm in lyric editor. [karaoke](#491@andy840119)
- Refactor lyric editor. [karaoke](#494@andy840119)
- Make calcuoation `caret position` abstract for better maintainance. [karaoke](#496#497@andy840119)

## Editor
- Adjust `color` in lyric editor. [karaoke](#462@andy840119)
- Show alert checker in lyric editor. [karaoke](#469@andy840119)
- Combine `cursor` and `moving cursor position` into single bindable in lyric editor. [karaoke](#473@andy840119)
- Auto move position while change selected lyric in lyric editor. [karaoke](#474@andy840119)
- Display invalid position at lyric editor. [karaoke](#482#483@andy840119)
- Adjust `style` in lyric editor. [karaoke](#485@andy840119)
- Enable to `click` time-tag to `navigation` to target time. [karaoke](#493@andy840119)
- Able to `right-click` to create new in lyric editor. [karaoke](#463@andy840119)
- Implement combine and separate lyric in lyric editor. [karaoke](#498@andy840119)

## Fix
- Fix cause error if move lyric time. [karaoke](#500@andy840119)

## Testing
- Writing test case to list all the `color` and `hex code` in `OverlayColourProvider`. [karaoke](#478@andy840119)