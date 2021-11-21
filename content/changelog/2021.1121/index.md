---
title: '2021.1121'
date: 2021-11-21
---

## Achievement
- Got a bike.
- Refactor exist skin format.
- issue `#888` has been created.

## Code quality
- Use enum dropdown instead. [karaoke](#892@andy840119)
- Use `OsuMarkdownTextFlowContainer` instead of `OsuMarkdownContainer` in editor section. [karaoke](#893@andy840119)
- Fix `FontUsageConvertorTest` run failed in osx. [karaoke](#909@andy840119)
- Should inherit `SnakeCaseKeyContractResolver` in `ShaderConvertor`. [karaoke](#915#918@andy840119)
- Should use `add()` instead of assign value in `json serializer settings`. [karaoke](#916#919@andy840119)
- Adjust namespace about skin. [karaoke](#922@andy840119)
- Adjust some interface about shader. [karaoke](#926@andy840119)

## Editor
- Click the note to open the pop-over in editor. [karaoke](#883#887@andy840119)
- Should be able to edit all note texts at the right side. [karaoke](#888#894@andy840119)
  ![](res/2021-11-21-14-50-29.png)
- Implement note edit mode by following how `ruby`/`romaji` do. [karaoke](#895@andy840119)

## Framework
- Fix outline shader render performance. [font-package](#78@andy840119)
- Not attach origin shader in ctor for able to save/load shader from json. [font-package](#84@andy840119)
- Should remove `new()` requirement in `AttachShader` function. [font-package](#88@andy840119)
- Should only place customized shader in step shader. [font-package](#89@andy840119)

## Performance
- Fix `outline shader` render performance. [karaoke](#885@andy840119)

## Skinning
- Refactor karaoke skin. [karaoke](#904@andy840119)
- Replace `KaraokeInternalSkin` to `DefaultKaraokeSkin`. [karaoke](#907@andy840119)
- Remove old karoake skin. [karaoke](#911@andy840119)
- Implement shader json convertor. [karaoke](#913@andy840119)
- Fix remain style skin error. [karaoke](#917@andy840119)
- Refactor style part in the skin system. [karaoke](#905@andy840119)
- Should apply `ColourConvertor` into `KaraokeSkinDecoder`. [karaoke](#912#920@andy840119)
- Refactor layout structor in karaoke skin. [karaoke](#921@andy840119)

## UX
- Adjust change log author width. [karaoke](#880#881@andy840119)
- Adjust changelog sizing. [karaoke](#882@andy840119)