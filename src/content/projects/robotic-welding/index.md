---
title: "robotic-welding"
description: "Gesture controlling a $20k robotic arm"
date: "Mar 01 2022"
repoURL: "https://github.com/aliadnani/robotic-welding"
image: "/robots.gif"
---

![robotic-welding demo](/robots.gif)

Gesture controlling a $20k robotic arm.

I wrote a program that lets you control a robotic arm using hand gestures captured via a camera. You can make it follow your hand position and orientation. I remember it also recognized a few specific gestures to trigger how many degrees of freedom the arm should move in.

 A lot of matrix math to get it work right. I remember I accidentally flipped a sign in one of the axises and the arm came crashing into the table - could have been expensive, but got away with it that time.