# Chordscape

An emotional instrument in your browser -- pick a colour mood from the dial, then tap, drag, and hold the canvas to play notes, bend chords, and watch a generative backing band build itself around you over time.

Part of the [sloopygames.com](https://sloopygames.com) collection.

## Play

Open `index.html` in any modern browser. Requires an internet connection on first load to fetch Tone.js (audio engine) and the Fraunces/JetBrains Mono fonts from CDN.

## How to Play

- Tap or drag anywhere on the canvas to play notes -- horizontal position selects the pitch within the active chord.
- Hold a tap to lock the current chord so it sustains while you play over it.
- Spin the emotion dial (bottom-left wheel) to shift between eight colour families (Yellow, Green, Blue, Cyan, Purple, Magenta, Red, Orange), each with its own key, scale, tempo, and timbre.
- Tap the emotion label to open a popover and pick one of the six specific emotions within the active colour family.
- A backing band assembles itself gradually over roughly three minutes -- Lead synth appears first, then Bass, Hats, Chords, and Arp, until the full arrangement is running.
- Press the record button (top-right) to capture your session and download it as an audio file.

## Controls

- **Tap** -- play a note at that position with a particle burst
- **Drag** -- stream flowing notes as you move across the canvas
- **Hold** -- sustain notes and lock the chord after ~0.4 seconds
- **Spin the dial** -- rotate through emotion families and moods
- **Tap emotion label** -- open the emotion picker for fine-grained selection
- **Arrow Left / Right** -- rotate the emotion dial by one step
- **Arrow Up / Down** -- increase or decrease the tempo (BPM)
- **Record button** -- start/stop audio recording; auto-downloads on stop

## Features

- 48 playable emotions across 8 colour families, each with its own musical key, scale, chord progression, tempo, drum character, and oscillator timbre.
- Generative backing band that grows in layers over ~3 minutes of play.
- Particle and canvas visual effects that react to every tap, drag, and hold.
- Full touch and multi-pointer support for mobile and tablet.
- Audio recording with one-tap download.

## Tech

- HTML, CSS, vanilla JavaScript
- HTML5 Canvas for visuals
- [Tone.js](https://tonejs.github.io/) v14.8.49 for Web Audio synthesis and scheduling (loaded from CDN)

## License

See repository for license details.
