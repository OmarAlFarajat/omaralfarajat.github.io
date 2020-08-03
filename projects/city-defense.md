---
layout: project
type: project
image: images/city-defense_thumbnail.jpg
title: City Defense
permalink: projects/citydefense
# All dates must be YYYY-MM-DD format!
date: 2020-06-13
labels:
  - C#
  - Unity
summary: A 3D real-time strategy game where you're tasked with defending a city from civil unrest.
---
**Source:** <a href="https://github.com/zee366/CityDefense"><i class="large github icon"></i>zee366/CityDefense</a>  
<br>
{% include youtubePlayer.html id="u7UmnszdAlU" %}  
<br>

<div class="ui medium rounded images">
  <img class="ui image" src="../images/city-defense/city1.png">
  <img class="ui image" src="../images/city-defense/city2.png">
  <img class="ui image" src="../images/city-defense/city3.png">
  <img class="ui image" src="../images/city-defense/city4.png">
  <img class="ui image" src="../images/city-defense/city5.png">
  <img class="ui image" src="../images/city-defense/city6.png">
</div>

## Introduction
City Defense is a realtime-strategy where you control a squad of police tasked with "bringing peace" to the city. NPCs are destroying the city and it's your job as police to ensure minimal property damage. Buildings and cars around you are on fire while nearby reporters take record of your behaviour. If you act too aggresively, you may lose funding. What kind of squad will you be?  

This is our team's submission for the COMP 476 game project at Concordia University. It was made using Unity game engine. GitHub was used for version control and GitHub Projects for task and issue tracking and team coordination. 

## Description
* Challenging AI system driven by a hierarchical task network (HTN) planner. NPCs move about and congregate in large mobs, forming plans of attack. A stamina based system regulates their attack or retreat behaviours. 
* *Public relations* resource system that regulates how much funding your squad will get based on their behaviour.
* System of night time lights bringing life to the city, including timed traffic lights.
* Well-featured UI that includes: tooltips, detailed minimap, ability buttons, city status, upgrades and resources. 
* A dense and convincing city map with hundreds of destructible objects with destruction animations and particle effects. 

## Controls
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 10px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 10px;word-break:normal;}
.tg .tg-fymr{border-color:inherit;font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-fymr">Input</th>
    <th class="tg-fymr">Action</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-0pky">Left-click</td>
    <td class="tg-0pky">Move to location</td>
  </tr>
  <tr>
    <td class="tg-0pky">Scroll up / down</td>
    <td class="tg-0pky">Zoom camera in / out</td>
  </tr>
  <tr>
    <td class="tg-0pky">Scroll wheel click + drag</td>
    <td class="tg-0pky">Orbit camera</td>
  </tr>
  <tr>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">Regular arrest</td>
  </tr>
  <tr>
    <td class="tg-0pky">2</td>
    <td class="tg-0pky">Faster arrest</td>
  </tr>
  <tr>
    <td class="tg-0pky">3</td>
    <td class="tg-0pky">Load rubber bullets</td>
  </tr>
  <tr>
    <td class="tg-0pky">4</td>
    <td class="tg-0pky">Fire guns</td>
  </tr>
  <tr>
    <td class="tg-0pky">5</td>
    <td class="tg-0pky">Use smoke grenade</td>
  </tr>
  <tr>
    <td class="tg-0pky">6</td>
    <td class="tg-0pky">Use water cannon</td>
  </tr>
  <tr>
    <td class="tg-0pky">7</td>
    <td class="tg-0pky">Load stun bullets</td>
  </tr>
  <tr>
    <td class="tg-0pky">8</td>
    <td class="tg-0pky">Reinforce squad with extra unit</td>
  </tr>
</tbody>
</table>