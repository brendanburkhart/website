---
title: "Path Bot"
date: 2018-10-27T01:46:56-07:00
---

After the 2018 FRC robotics competition season last spring, I decided that my team's robots needed an upgrade to their autonomous navigation capabilities. Over the summer, I began work on new navigation software for our robots with another programmer from my robotics team, Caleb Eby. The project is still a work in progress but an initial version should be done within the next couple of weeks. The project can be found at https://github.com/Pigmice2733/path-bot.

The previous version of the robot navigation software used a pure pursuit controller to follow a segmented path, and was relatively finicky and required quite a bit of careful tuning before it performed well on a given path. The newer version uses quintic splines to represent paths, and will hopefully require significantly less tuning.
