---
title: "2024.0228"
date: 2024-02-28
---

## Achievement

- Go to japan for two weeks.
- Go to aviation museum near the airport. It's a good deal using the cheap price to play the flight simulator with expensive device.
- Eat some special meats that hard to get in my country, such as rabbit and raccoon. The next time might be crow i guess(?)
- Go to comiket.
- WFJ for few days.
- Have a new year in japan.
- Visit 3 ski resort haven't visit before.
- Spend some times playing `テトテ×コネクト` in ronud1.
- Buy some anime blu-ray disks.
- Go to the street near the `Tsukishima` station. The whole street(maybe with more than 40 stores) all selling the damn monjayaki.
- Have one week holiday at february. Relax such a long time is damn happy.

I dont't want to back to work now ;\_;

## Code quality

- Refactor the logic to get the issue icon in the lyric editor. [karaoke](#2154@andy840119)
- Issue tooltip shouod show the same things in the issue container. [karaoke](#2155@andy840119)
- Move some component out of shared component. [karaoke](#2156@andy840119)
  > component in the shared namespace should be more generic.
- Wrap the logic to get the changelog api request. [karaoke](#2157#2158@andy840119)
  > All api request should be wrap into the request class like how lazer did.
- Clean-up the code in the airport. [karaoke](#2159@andy840119)
- Customized pop-up dialog should belongs to overlay namespace. [karaoke](#2163@andy840119)
- Refactor the changelog again to let the class structure more understandable. [karaoke](#2164@andy840119)
- Rename from "romaji" into "romanization" in the time-tag. [karaoke](#2165@andy840119)
  > "Romaji" is the romanization for japan only.
- Deep-clone the time-tag should copy the romanization also. [karaoke](#2166@andy840119)

## Fix

- [Close duplicated] Fix ruby generator not work due to packing tool. [karaoke](#1319@andy840119)
- Upgrade the project to `.net8`, includes:
  - The main project. [karaoke](#2171@andy840119)
  - Project for display karaoke font. [font-package](#440@andy840119)
  - Project for dealing with microphone voice. [microphone-package](#351@andy840119)
    > Because lazer moved to `.net8` also.
- Remove the packing dll tool. [karaoke](#2172@andy840119)
  > Because recommend copy all related dlls into the ruleset folder instead of the packed one.  
  > Also, the packing tool is not worked in the `.net8`. It's time to say goodbye.
