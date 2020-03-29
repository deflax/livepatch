digital music setup deflax 2020

software:
- native instruments traktor pro 3
  provides:
    - master clock via generic midi
    - 3d party audio beatmatched and routed via jack (audio only, no timeline sync)

- propellerhead reason 10
  provides:
    - mixing to 1/2
    - dsp
    - monitoring to 3/4
    - modular synth
    - drum machines
  accepts:
    - mic/line in 1/2

controllers:
- akai midi mix
  controls:
    - reason mixers
    - dsp
- novation remote le 25
  controls:
    - modular synths
    - drum machines

audio:
- jack:
  provides:
    - audio input for reason
  accepts:
    - audio output for traktor
- focusrite scarlett 2i4 2nd Gen
  provides:
    - main output 1/2
    - headphones output 3/4
  accepts:
    - mic/line in 1/2

streaming:
- obs:
  accepts:
    - main output 1/2
    - camera1: display capture of audio software
    - camera2: logitech c922 to record controllers
    - camera3: android ip cam (optional)