---
layout: project
type: project
image: images/kinect-mocap_thumbnail.jpg
title: Kinect Motion Capture
permalink: projects/kinectmocap
# All dates must be YYYY-MM-DD format!
date: 2019-11-01
labels:
  - C++
  - OpenGL
summary: Real-time motion capture on a 3D character with recording and playback.
---
**Source:** <a href="https://github.com/OmarAlFarajat/Kinect-Motion-Capture"><i class="large github icon"></i>OmarAlFarajat/Kinect-Motion-Capture</a>  

**Attributions:**
- Prof. Tiberiu Popa COMP 477 Code, <a href="https://github.com/KevinZkX/comp477-assignment"><i class="large github icon"></i>KevinZkX/comp477-assignment</a>  

- Kinect V1 SDK Setup,<a href="https://github.com/kyzyx/Tutorials/tree/master/KinectSDK/1_Basics"><i class="large github icon"></i>kyzyx/Tutorials/tree/master/KinectSDK/1_Basics</a>  

<br>
{% include youtubePlayer.html id="YRt8sM6gbdI" %}  
<br>

## Introduction
Given a code base of a skeleton-mesh animation system (coded in C/C++ using OpenGL/GLUT), interface it with a Kinect device to capture and play back human movement. Human movement animates a 3D character in real-time. The animations can be recorded and saved. 

## Notes
- Make sure to run in Release mode and x86 configuration.
- Inputs are mixed between the console window and the glut window. Be mindful of which window is currently focused. Enter the key presses while focused on glut window, then switch to console window if prompted to enter a file name.

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
    <td class="tg-0pky">Q</td>
    <td class="tg-0pky">Quit</td>
  </tr>
  <tr>
    <td class="tg-0pky">R</td>
    <td class="tg-0pky">Reset skeleton</td>
  </tr>
  <tr>
    <td class="tg-0pky">L</td>
    <td class="tg-0pky">Load animation</td>
  </tr>
  <tr>
    <td class="tg-0pky">S</td>
    <td class="tg-0pky">Save animation</td>
  </tr>
  <tr>
    <td class="tg-0pky">1</td>
    <td class="tg-0pky">Select Matrix Interpolation</td>
  </tr>
  <tr>
    <td class="tg-0pky">2</td>
    <td class="tg-0pky">Selecter Euler Interpolation</td>
  </tr>
  <tr>
    <td class="tg-0pky">3</td>
    <td class="tg-0pky">Select Quaternion Lerp</td>
  </tr>
  <tr>
    <td class="tg-0pky">4</td>
    <td class="tg-0pky">Select Quaternion Slerp</td>
  </tr>
  <tr>
    <td class="tg-0pky">P</td>
    <td class="tg-0pky">Play animation</td>
  </tr>
  <tr>
    <td class="tg-0pky">J</td>
    <td class="tg-0pky">Speed up animation</td>
  </tr>
  <tr>
    <td class="tg-0pky">K</td>
    <td class="tg-0pky">Slow down animation</td>
  </tr>
  <tr>
    <td class="tg-0pky">M</td>
    <td class="tg-0pky">Toggle animation or editing mode</td>
  </tr>
  <tr>
    <td class="tg-0pky">=</td>
    <td class="tg-0pky">Add keyframes</td>
  </tr>
  <tr>
    <td class="tg-0pky">-</td>
    <td class="tg-0pky">Back to first keyframe</td>
  </tr>
  <tr>
    <td class="tg-0pky">Space</td>
    <td class="tg-0pky">Record</td>
  </tr>
  <tr>
    <td class="tg-0pky">Left-click</td>
    <td class="tg-0pky">Rotate camera or move joints</td>
  </tr>
  <tr>
    <td class="tg-0pky">Right-click + drag</td>
    <td class="tg-0pky">Pan camera</td>
  </tr>
  <tr>
    <td class="tg-0pky">Scroll wheel</td>
    <td class="tg-0pky">Zoom in camera</td>
  </tr>
</tbody>
</table>