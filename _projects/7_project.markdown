---
layout: page
title: chi-crime
description: crime visualization and avoidance utility
img: /assets/img/7_project.png
---

<img class="col three" src="{{ site.baseurl }}/assets/img/7_project.png">

[source code](https://github.com/wilimitis/Chi-Crime)

A frontend utility which pulls data from Socrata's open Chicago crime api and utilizes the Google maps toolkit to let users request a route from A to B. The route is then scored based on the number of recent crimes which have occurred within a specified proximity of any point on the route.

The user is then able to drag the route and have it rescored in real-time, enabling them to manually avoid recent hot zones. Since I had yet to learn of more efficient heuristic-oriented search algorithms I naïvely chose to consider the project complete, but am eager to reopen it at some point in the future.

This project was completed independently while interning at Motorola Solutions during summer 2015 of my sophomore year at UIC upon early completion of my internship project.
