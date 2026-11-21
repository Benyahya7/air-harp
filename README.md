# Air Harp

Play glowing strings in mid-air with your webcam. A web app inspired by
[@sonicdeadhorse's air harp](https://www.instagram.com/reel/Df6dCTnMZkX/).

## How it works

- Your webcam watches your hands. MediaPipe hand tracking finds 21 joints
  per hand, entirely in the browser — no video ever leaves your device.
- Glowing strings stretch between your fingertips. String length sets the
  pitch; a quick flick plucks the string, with sparks running along it.
- The sound is synthesized live with a Karplus-Strong plucked-string model.

## Play it

Open the site (GitHub Pages link below), allow the camera, and hold your
hands up an arm's length away. Stretch a string between two fingertips to
change its pitch, flick it fast to pluck. If the camera is blocked, the
built-in touch harp plays the same instrument by dragging across the strings.

## Run locally

Just open `index.html` in a browser — it needs camera access, so serve it
over `https` or `localhost` (for example `python3 -m http.server`).
