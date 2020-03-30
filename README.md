digital music setup deflax 2020

software:
- jack:
  - links:
    - from system capture mic to traktor
    - from traktor to ableton
    - from ableton to system playback
- ableton live lite 10:
  - provides:
    - traktor decks A to D tracks via in 1/2, 3/4, 5/6, 7/8
    - reason host via rewire
    - main mixer output via out 1/2
    - cue via out 3/4
- native instruments traktor pro 3
  - provides:
    - master clock via ableton link
    - 3d party tracks beatmatched and routed via jack (audio only, no timeline sync)
- propellerhead reason 10
  - provides:
    - effects dsp
    - modular synths
    - drum machines

controllers:
- akai midimix
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
