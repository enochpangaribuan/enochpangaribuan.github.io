---
layout: project
type: project
image: img/IALogo.png
title: "Intergalactic Attack"
date: 2026-28-01
published: true
labels:
  - JavaScript
summary: "A strategic spaceship game."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

Space Battle is a turn-based strategy game where the player commands a spaceship in combat against an enemy vessel. Each turn, the player chooses an action such as firing lasers, launching high-damage missiles, or boosting defensive shields. Every decision matters — missiles consume energy, shields can absorb damage, and the enemy attacks back with unpredictable force.

The game challenges players to manage resources, balance offense and defense, and survive long enough to destroy the opposing ship. With randomized damage and multiple player stats (health, shields, and energy), each playthrough offers a slightly different outcome, encouraging strategic thinking and replayability.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
