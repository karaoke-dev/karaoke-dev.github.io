---
title: '2023.0606'
date: 2023-06-06
---

## Achievement
- Reduce the time on this project recently.
- Remove most nullable disable annotation in the main project.
- Back to the office ;_;
- 和主管討論留職停薪。如果通過的話，接下就能更有更多的時間先把這份專案弄到一個段落，還有年底的日本旅遊就有著落了。

## Beatmap
- `Ruby`/`Romaji`'s index should be the char index. [karaoke](#2009@andy840119)
    - Should adjust the [lyric parser](https://github.com/karaoke-dev/LrcParser/pull/44) first.
    - Then, make the font framework happy. [font-package](#353@andy840119)
    - Finally, adjust the main project. [karaoke](#2015@andy840119)

## Code quality
- Use `= null!` to replace the `[AllowNull]` attribute. [karaoke](#1987#1988@andy840119)    
    Change this:
    ```csharp
    [Resolved, AllowNull]
    private EditorBeatmap beatmap { get; set; }
    ```

    Into this:
    ```csharp
    [Resolved]
    private EditorBeatmap beatmap { get; set; } = null!;
    ```
- Remove the nullable disable annotation in some location:
    - Remove the nullable disable annotation in the `editor`. [karaoke](#1989@andy840119)
    - Remove the nullable disable annotation in the `overlay` namespace. [karaoke](#1990@andy840119)
    - Remove the nullable disable annotation in the `UI` namespace. [karaoke](#1991@andy840119)
    - Remove the nullable disable annotation in the `Statistics` namespace. [karaoke](#1992@andy840119)
    - Remove the nullable disable annotation in the `setting page`. [karaoke](#1994@andy840119)
    - Remove the nullable disable annotation in the `skin editor`. [karaoke](#1996@andy840119)
    - Remove the nullable disable annotation in the `lyric editor`. [karaoke](#2003@andy840119)
    - Remove the nullable disable annotation in the `import lyric` namespace. [karaoke](#2005@andy840119)
    - Remove the nullable disable annotation in the `singer editor`. [karaoke](#2010@andy840119)
    - Remove the nullable disable annotation in the `whole beatmap editor`. [karaoke](#2014@andy840119)
- Adjust `permit null` in dependency injection. [karaoke](#1993@andy840119)
- Remove all `aaa.invoke()` usage. [karaoke](#2006#2016@andy840119)

## Editor
- `OpacityButton` should have the `current` property like other shared component. [karaoke](#2002@andy840119)
- Separate the base class for those "lyric index" based caret position algorithm. [karaoke](#2017#2018@andy840119)   
    For now, we have two lyric text-based caret position algorithm:
    - `CharGapCaretPositionAlgorithm`: adjust the caret index between text gap.
    - `CharIndexCaretPositionAlgorithm`: adjust the caret index between chars.
- Combine the `Validate` and `PositionMovable` in the `CaretPositionAlgorithm` because pre-validator in the caret position algorithm usually check the same things as what `PositionMovable` did. [karaoke](#2020@andy840119)
- Algorithm should not accept the null caret position index. [karaoke](#2021@andy840119)
- Implement base interface for able to change the end index caret position. [karaoke](#2022@andy840119)

## Setting
- Fix the broken preview area in the setting menu. [karaoke](#1998@andy840119)
- Fix cannot open the karaoke config page. [karaoke](#1999@andy840119)
- Remove assign language in the main setting overlay because does not have the global popover container now. [karaoke](#2000@andy840119)

## UI/UX
- Make language selector able to select null language. [karaoke](#2001@andy840119)