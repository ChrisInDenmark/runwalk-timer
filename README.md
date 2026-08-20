# RunWalk Timer

A simple Run/Walk interval timer designed primarily for running with an iPhone.

This is an early version and is currently being tested.

## Current Features

* Configurable total workout time
* Configurable running interval
* Configurable walking interval
* Start, pause and resume
* Skip current interval
* Stop and reset
* Spoken **RUN** and **WALK** prompts
* Optional beep at interval changes
* Spoken 5-second countdown
* Remembers previous settings
* Designed to run from the iPhone Home Screen
* Attempts to keep the screen awake during a workout
* Offline support after the app has been loaded

## Example

For a 20-minute workout:

* Run: 4 minutes
* Walk: 1 minute
* Total: 20 minutes

The timer automatically alternates between running and walking until the workout is complete.

## Install on iPhone

1. Open the hosted RunWalk Timer page in Safari.
2. Tap the **Share** button.
3. Select **Add to Home Screen**.
4. Tap **Add**.
5. Launch **RunWalk** from the new Home Screen icon.

## Status

**Version: 0.1 – First test version**

The main goal of this version is to verify reliable operation on an iPhone during an actual run.

Things still to test:

* Timing accuracy while running
* Voice prompts with the phone locked
* Audio behavior with AirPods/headphones
* Screen wake-lock behavior
* Pause/resume behavior
* Recovery when switching away from the app
* Offline operation
* General usability while running

## Planned Improvements

Possible improvements after real-world testing:

* Quick presets such as 1:1, 2:1 and 4:1
* Better audio cues
* Improved countdown
* Larger running controls
* Workout history
* Optional warm-up/cool-down
* Improved locked-screen/background behavior

## Files

* `index.html` – RunWalk application
* `manifest.webmanifest` – Home Screen/PWA configuration
* `service-worker.js` – Offline support
* `icon-192.png` – App icon
* `icon-512.png` – App icon

---

This is an experimental personal project. Version 0.1 should be considered a test build rather than a finished running app.
