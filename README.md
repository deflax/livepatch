digital music setup deflax 2020

software:
- jack:
  - links:
    - from system capture mic to reason (audio in)
    - from traktor to reason (4 stereo decks)
    - from reason to system playback (monitor out, cue out)
    - from reason to reaper (monitor out)
- reaper:
  - links:
    - bridge between jackrouter and obs via ReaRoute (as obs-asio do not like jackrouter for some reason and i failed compiling it on my own with the portaudio branch :)
- native instruments traktor pro 3
  - provides:
    - 4 decks beatmatched and routed via jack (audio only, no timeline sync)
- propellerhead reason 10
  - provides:
    - simplified model 1 style EQ
    - 8 channel mixer
    - effects dsp
    - drum machines
    - modular synths

controllers:
- akai midimix
  - controls:
    - mixer (faders 1-8)
    - cue out (rec arm 1-8)
    - eq (knob 1-8 mid + bottom)
    - fx (knob 1-8 top)
    - monitor out
- novation remote le 25
  - controls:
    - drum machine parameters  (knob 1-4 A)
    - drum machine mute (button 1-4 A)
    - drum machine pattern (button 5-8 A)
    - fx rack (knob 5-9 A)
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
