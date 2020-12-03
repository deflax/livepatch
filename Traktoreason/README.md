digital music setup deflax 2020

software:
- jack:
  - from system capture to reason (mic/line input 1/2)
  - from traktor to reason (4 stereo decks)
  - from reason to system playback (monitor output 1/2, cue out via headphones 3/4)
  - from reason to reaper (monitor out)
- reaper:
  - bridge between jackrouter and obs via ReaRoute (as obs-asio do not like jackrouter for some reason and i failed compiling it on my own with the portaudio branch :)
- native instruments traktor pro 3
  - 4 decks beatmatched and routed via jack (audio only, no timeline sync)
- propellerhead reason 10
  - simplified model 1 style EQ
  - 8 channel mixer
  - effects dsp
  - drum machines
  - modular synths
  - controllers:
    - akai midimix:
      - mixer (faders 1-8)
      - cue out (rec arm 1-8)
      - eq (knob 1-8 mid + bottom)
      - fx (knob 1-8 top)
      - monitor out
    - novation remote le 25:
      - drum machine parameters  (knob 1-4 A)
      - drum machine mute (button 1-4 A)
      - drum machine pattern (button 5-8 A)
      - fx rack (knob 5-9 A)
      - modular synths (keys)
      - tempo decimal 000-500, 500-999 (pitch)
      - audio capture volume (mod)
      - audio capture fx (trackpad x1,x2)
- obs:
  - accepts:
    - input:  ReaRoute out
    - camera1: display capture of audio software
    - camera2: logitech c922 to record controllers
    - camera3: android ip cam (optional)


![JackRouter](https://raw.githubusercontent.com/deflax/livepatch/master/screenshots/live-obs.png)

![Tractoreason](https://raw.githubusercontent.com/deflax/livepatch/master/screenshots/traktoreason.png)