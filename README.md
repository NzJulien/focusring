# FocusRing

> A Pomodoro focus timer with a circular SVG progress ring, a session log, and a 7-day focus chart. No AI, no backend.

## Live Demo
https://nzjulien.github.io/focusring

## Features
- Focus / Short Break / Long Break phases with a classic 25-5-15 default cycle
- Circular SVG progress ring that fills as time elapses, color-coded per phase
- Configurable durations and number of sessions before a long break
- Optional auto-start of the next phase
- Audio chime on phase completion (Web Audio API oscillator — no sound files)
- Live browser tab title showing remaining time while running
- Session log of every completed phase, with timestamps
- 7-day focus chart (hand-drawn on canvas, no chart library)
- Today's stats: sessions completed, total focus minutes
- Everything persists in localStorage

## Stack
- Vanilla HTML / CSS / JavaScript
- SVG for the progress ring
- Canvas 2D for the weekly bar chart
- Web Audio API for the completion chime
- Zero dependencies, zero build step

Made by NzJulien
