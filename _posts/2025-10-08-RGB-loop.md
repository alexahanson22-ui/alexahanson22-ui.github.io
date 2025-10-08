---
layout: post
title: RGB Loop
subtitle: Creating a loop in C that has an extra variable and terminates at a certain integer (in this case, 250)
author: Alexa Hanson
---

In this project, I learned how to create a "while" loop in C that terminates at a certain integer. I started at 0, and in increments of 10 (mod 10) the output would be RED 3x, then GREEN, then BLUE and it would repeat every 10 until 250.

A hint is that doing the work in increments really helped. I started out by just creating the color repetition up to 9 times, and then figured out that I needed to reset the color repetition back to 0 for it to start again. Slowing down my work helped me understand what to do.

## The output


![RGB loop output](https://alexahanson22-ui.github.io/assets/img/rgbloopoutput.png){: .mx-auto .d-block }
