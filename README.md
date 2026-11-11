# RAMP RIOT

An animal stunt-bike racer with a built-in course editor. Pick a rider (fox, wolf, croc, tiger, panda or rhino), pick a bike, build a track out of jumps, loops, berms and obstacles, then race it.

![Riders](images/riders.png)

## Play

The whole game is a single file, `index.html`. Open it in a browser, or serve the folder with any static host (GitHub Pages works: Settings → Pages → deploy from the `main` branch).

It loads Three.js from the jsDelivr CDN, so it needs an internet connection.

## Features

- Modes: race, stunt (score), drag (400 m), tour, and free ride
- Course builder with straights, turns, climbs, jumps, loops, berms, boost pads and whoops
- Scenery themes with a synth soundtrack
- Air tricks, wheelies, stunt replays and photo mode
- Ghosts, medals, high scores and a daily challenge
- Keyboard, gamepad and touch controls (buttons, tilt or swipe)
- In-game "How to play" guide and hands-on tutorial

## Ads

Ad slots are configured in the `ADS` object in `index.html`. Replace the placeholder AdSense client and slot ids with your own; ads only load when the file is self-hosted.
