digital music setup deflax 2020

software:
- jack:
  - links:
    - from system capture mic to reason
    - from traktor to reason
    - from reason to system playback
- native instruments traktor pro 3
  - provides:
    - 3d party tracks beatmatched and routed via jack (audio only, no timeline sync)
- propellerhead reason 10
  - provides:
    - effects dsp
    - modular synths
    - drum machines

controllers:
- akai midimix
  - controls:
    - mixers
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
