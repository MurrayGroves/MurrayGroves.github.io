---
title: Overwatch SSE3 Integration
description: Allows user to set effects on their SteelSeries devices based on Overwatch cooldowns.
date: "2019-05-02T19:47:09+02:00"
jobDate: 2019
work: [Python]
techs: [Python]
designs: []
thumbnail: overwatch-sse3-integration/thumbnail.png
projectUrl: https://github.com/MurrayGroves/Overwatch-SSE3-Integration

---

One of the many parts of Overwatch is cooldown management, it can be hard to know whether your abilities are available in the middle of a battle, to fix this issue I made a Python program that takes determines a user's current hero by taking screenshots of the bottom left of the screen and running them through a comparison algorithm. Whenever it detects a keypress that activates an ability it starts a timer and at the end uses the SteelSeries SDK to interact with their devices in whichever way the user selects. For example, sending vibrations to their mouse.
