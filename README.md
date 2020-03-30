digital music setup deflax 2020

software:
- jack:
  - links:
    - from system capture mic to traktor
    - from traktor to ableton
    - from ableton to system playback

- ableton live lite 10:
  - provides:
    - mine mixer output to 1/4
    - cue to output 3/4
    - rewire host
    - traktor decks A to D via in 1/2, 3/4, 5/6, 7/8

- native instruments traktor pro 3
  - provides:
    - master clock via ableton link
    - 3d party audio beatmatched and routed via jack (audio only, no timeline sync)

- propellerhead reason 10
  - provides:
    - effect dsp
    - modular synth
    - drum machines


controllers:
- akai midi mix
  - controls:
    - ableton main mixer
- novation remote le 25
  - controls:
    - modular synths
    - drum machines

hardware:
- focusrite scarlett 2i4 2nd Gen
  - provides:
    - main output 1/2
    - headphones output 3/4
  - accepts:
    - mic/line in 1/2

streaming:
- obs:
  - accepts:
    - input:  output 1/2
    - camera1: display capture of audio software
    - camera2: logitech c922 to record controllers
    - camera3: android ip cam (optional)
