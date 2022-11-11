# KeyboardLayouts
Experimenting with keyboard layout and layers: 
- Currently using vanilla colemak with a slightly modified dreymar's extend layer on normal keyboards.

ell into the mechanical keyboard rabbit hole, planning to get a 75% QMK keyboard and a 42-key QMK keyboard for use with steno/plover.

and implementing a modified version of dreymar's extend layer to keep muscle memory. 

To find/build QMK implementation for mech keyboard?


## Feature requirements

Values:
- Left hand should have easy access to functions and commands while right hand is occupied with pen/paper or other stuff.
- Able to stay mostly within home row when typing with both hands
- Access to mouse control to avoid reaching the mouse for trivial stuff.
- Able to easily switch between normal keyboard and 42-key keyboard with minimal difference in muscle memory.
- Normal keyboard layers should be easy to implement with AHK or other non-admin priviledge software on work computer.

Caps lock as extend layer (layer 1) on both normal keyboards and 42-key keyboards.
- Nav keys on right side, mod keys and mouse scroll wheel control on left side.
- Backspace/delete easily accessible with left hand.
- Num row on normal vs 42-key keyboard?

Two or three thumb layers (layer 2, 3, 4) on 42-key keyboards for number, symbols, function keys, media controls, and mouse control, two keys on right thumb to be allocated for layer activation: Either key A, key B, or key A+B for the three layers. 

## Dreymar's extend layer

Based on https://dreymar.colemak.org/layers-extend.html

Unable to run the original EPKL implementation from https://github.com/DreymaR/BigBagKbdTrixPKL on my work computer so used the AHK implementation below instead, albeit with several modifications.
- AHK implementation: https://github.com/stevep99/keyboard-tweaks/blob/master/ExtendLayer
- Karabiner-elements implementation: https://github.com/ProfXwing/extend-karabiner

## 42-key layout

Layouts for reference:
- Corn1sher 42-key layout: https://www.reddit.com/r/ErgoMechKeyboards/comments/p38oji/corn1sher_personal_keymap/
- Corne-ish-zen 42-key layout: https://github.com/Valarauka-GH/zmk-config-Corne-ish-Zen/tree/main/config
- Miryoku 36-key layout: https://github.com/manna-harbour/miryoku/tree/master/docs/reference

Corn1sher and Corne-ish-zen for reference, somewhat similar to dreymar's extend layer. Miryoku uses home row mods, any way to adapt it to dreymar and without home row mods?
