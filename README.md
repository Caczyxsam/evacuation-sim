# Crowd Evacuation Simulator

A single self-contained HTML file (all CSS and JS inline, no dependencies, no build step) that runs a top-down crowd-evacuation demo on an HTML5 canvas.

It's a crowd evacuation simulator: tap "Sound Alarm" to watch 10 sped-up timelapse runs of people fleeing a room through its exits, reporting the average evacuation time.

## Run it

Live demo: **https://caczyxsam.github.io/evacuation-sim/**

Or open `evacuation-sim.html` in any modern browser — that's it.

## Features

- **Top-down room** with perimeter walls and furniture (sofa, table, chairs, shelf) people route around.
- **Three exits.** Click an exit before the alarm to close it and see how it changes the evacuation.
- **Idle behaviour:** people casually mill about or stand still until the alarm.
- **Flow-field pathfinding:** a Dijkstra distance map routes everyone around walls and obstacles to the nearest exit.
- **Crowd dynamics:** people jam at doorways, slow down (and turn yellow) when packed in, and occasionally stumble (turn red, freeze briefly).
- **Timelapse analysis:** the alarm plays the evacuation 10 times, each with a fresh random spread, starting slow then speeding up, and reports the average / fastest / slowest evacuation time for the current exit layout.
- **Mobile friendly:** fluid canvas, touch-friendly controls and exit tapping.
