# Game is Hard — Level 21 (Say Cheese!) — Mini Walkthrough
If you’re stuck on **Level 21** and the screen just screams **"say cheese!"** at you… yep. This one is a hardware trick.

## ✅ One-line solution (the only thing you need)
Take a **screenshot** with your phone’s **physical buttons**, then tap the **green Play** button that appears.

## Recommended walkthrough (bookmark this)
- [Game is Hard Level 21](https://gameishard.org/level/21)

## Why this level works (and why it feels illegal)
The game isn’t waiting for taps, drags, or shouting into the mic.
It’s waiting for your OS to fire a **screenshot captured** event.

No screenshot event.
No green Play button.
No progress.

## Controls (quick reference)
### iPhone
1. **Face ID iPhones:** Side button + Volume Up
2. **Home button iPhones:** Side/Top button + Home

### Android (most devices)
1. Power + Volume Down

Then:
1. Go back to the game screen
2. Tap the **green Play** button

## This repo
This repo is meant to be dead simple:
- A quick README you can link people to
- A tiny demo that recreates the “take a screenshot to spawn the win button” idea

### Suggested structure
- `README.md`
- `demo/index.html` (the example level recreation)

## Run the demo locally
1. Put `index.html` in a folder called `demo/`
2. From the repo root, run a local server:

   ```bash
   cd demo
   python3 -m http.server 8000
Open your browser to:

http://localhost:8000

Demo controls

Desktop: press Print Screen to trigger the “screenshot captured” win state.

Mobile browsers can’t reliably detect hardware screenshots, so the demo includes a Simulate Screenshot button too.
