thumb cluster
=============
problems with the default
- default windows
  - ~~prioritizes control~~
  - ~~command and atl are only single hand~~
- default mac
  - correctly prioritizes command
  - option only on left
  - control only on right

changes
- prioritize command, option, control, shift modifiers (in order)
- should modifier layout be the same on both hands?
  - the default mac layout uses this approach
  - the top to bottom order of control and option could be swapped on each side
  - would not prevent pressing option and control at the same time
- it is convenient to press control and option at the same time with the thumb

todo
====
- simplify shift: use thumb cluster or pinky finger
  - what should be mapped to the remaining key?
- start using keypad layer (number pad)
  - change the keypad layer from toggle to momentary
    - should keypad layer key be changed to momentary and double tap?
- start using caps-word feature
  - map capslock to caps-word
  - add cursor keys to continue-list
  - continue caps word until whitespace or through symbols
- what could the macro keys be used for?
- consider never mapping home/end/pageup/pagedown keys
  - consistent use modifier key combinations
  - what are the readline shell equivalents?
- should the globe key be mapped?
- consider using a layer for arrow keys

left hand operation
===================
- want to be able to leave hand on trackpad
- reaching for space a lot with left hand and end up hitting the backspace key
- consider swapping backspace/delete with space/return
  - the function layer key is easy to reach with the left pinky and right thumb
  - consider other left hand modifier key

building firmware
=================
- execute online [keymap-editor](https://nickcoutsos.github.io/keymap-editor/) linked to forked github repository
- save to push changes to forked repository
- docker service needs to be running
- execute `make`
- flash each side of the keyboard
  - [Flashing firmware](https://github.com/KinesisCorporation/Adv360-Pro-ZMK?tab=readme-ov-file#flashing-firmware)
  - Tips and Tricks
    - mod hotkey 1 left side
    - mod hotkey 3 right side
  - Step-by-Step Firmware Flashing Instructions6'
    - paper clip each side
change log
- initial commit with the format changes and no key mappings
- thumb cluster
- function layer left hand space and enter
