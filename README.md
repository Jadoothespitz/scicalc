# SciCalc Notepad

Default iPhone calculator sucks. Other calculator apps available on App Store were full of ads, and I didn't like all of them. So I made my own calculator I've dreamed with Claude Code for personal use.
A web-based scientific calculator with a notepad-style interface. Calculations proceed line by line, and you can scroll up to see previous results.

**Try it live:** [https://jadoothespitz.github.io/scicalc/](https://jadoothespitz.github.io/scicalc/)

## Features

- **Notepad-style layout** -- each calculation is a new line, with full scrollable history
- **Scientific functions** -- sin, cos, tan, inverse trig, log, ln, sqrt, cbrt, factorial, powers, and more
- **DEG / RAD toggle** -- switch between degrees and radians for trig functions
- **8 color themes** -- Solarized Light, Paper, Rose, Nord Frost, Midnight, Dracula, Monokai, Solarized Dark
- **Persistent history** -- calculations and theme choice are saved in localStorage, so nothing is lost on refresh
- **PWA** -- installable on phones and works offline
- **ANS key** -- reuse the result of the last calculation

## Built with

HTML, CSS, and vanilla JavaScript -- single file, no frameworks, no dependencies.
