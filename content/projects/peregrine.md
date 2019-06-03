---
title: 'Peregrine'
date: 2019-6-3T01:27:00-07:00
---

Peregrine is a web app for collecting and analysing data from robotics competitions. It is a project created for my robotics team, which I developed alongside two other programmers from our team, Frank Harding and Caleb Eby. Peregrine was created to move our team away from our old, tedious method of paper-forms-and-spreadsheets style data collection to a faster and easier online platform, with builtin data processing and analytics.

We used the [first version](https://pigmice.ga/) of Peregrine at several competitions in the 2018 season year and loved it. We also gained quite a bit of insight into how we could improve it, and launched a [new and improved version](https://peregrine.ga/) before the 2019 season. The source for the v1 [frontend](https://github.com/Pigmice2733/scouting-frontend) and [backend](https://github.com/Pigmice2733/scouting-backend) are on GitHub, as is the v2 [frontend](https://github.com/Pigmice2733/peregrine-frontend) and [backend](https://github.com/Pigmice2733/peregrine-backend).

The frontend is a PWA (progressive web application) written in Typescript using (p)React and hosted on the static content hosting service Netlify. The backend is written in Go with a PostgreSQL database and is hosted in either Google Cloud during the season, or a server owned by a team member during the offseason.

<p>
    <img width=200em src="/img/v1_events.png" alt="Main page, listing current and upcoming events nearby" style="padding:0 3em 2em 0" align="left"/>
    <img width=200em src="/img/v1_match.png" alt="Page detailing upcoming match at a competition" style="padding:0 3em 2em 0" align="left"/>

    The home screen of Peregrine contains a list of current or upcoming FRC robotics competitions happening near you, and from there you can explore a specific event, compare the capabilities of the teams competing, and analyse how their performance changed over the course of the 2-3 day competition.

</p>
