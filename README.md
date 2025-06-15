# KeyboardLayouts

A place to store my keyboard layout config files. Currently using the colemak layout with an extend layer, mainly via the Keychron K3 Pro keyboard.

## Extend layer config/scripts

Original config/scripts based on [Dreymar's extend layer](https://dreymar.colemak.org/layers-extend.html).

- `archive/extend.ahk` - Autohotkey script for use in Windows (need to compile, can run without admin).
- `archive/karabiner_extend.json` - Karabiner config for use in macOS.
- `archive/keychron_k3_pro.json` - VIA config for Keychron K3 Pro keyboard.

Alternative version with vim-style arrow keys also available.

- `archive/extend_vim.ahk` - Autohotkey script for use in Windows (need to compile, can run without admin).
- `archive/karabiner_extend_vim.json` - Karabiner config for use in macOS.
- `archive/keychron_k3_pro_vim.json` - VIA config for Keychron K3 Pro keyboard.

Eventually switched from the original Dreymar version to the vim-style arrow keys version. Currently experimenting with a slightly modified layout, `keychron_k3_pro_20250615.json`, and mostly stopped using the AHK and Karabiner version. See below for screenshots of current layout.

Default layer for mac, MO(0):
![default layer for mac](https://github.com/bk7312/keyboardLayouts/blob/main/img/l1-mac.png)

Extend layer for mac, MO(1):
![extend layer for mac](https://github.com/bk7312/keyboardLayouts/blob/main/img/l2-mace.png)

Default layer for windows, MO(2):
![default layer for window](https://github.com/bk7312/keyboardLayouts/blob/main/img/l3-win.png)

Extend layer for windows, MO(3):
![extend layer for window](https://github.com/bk7312/keyboardLayouts/blob/main/img/l4-wine.png)

Reference:

- Original EPKL implementation: https://github.com/DreymaR/BigBagKbdTrixPKL
- AHK implementation: https://github.com/stevep99/keyboard-tweaks/blob/master/ExtendLayer
- Karabiner-elements implementation: https://github.com/ProfXwing/extend-karabiner
