# zmk-config
This is a version of ZMK for the Corneish Zen Group Buy Rev 2.
It has been optimized for the use of three different cases:
1. Mac OS X
2. Windows / Linux
3. Emacs

The basic layout is Dvorak - used on MACBASE/EMACS/WINLIN
-
Each base layer has an associated set of support layers:
1. Number
2. Symbol
3. Navigation

Other layers:
KEYBD: This is a layer for adjusting keyboard settings, mainly for bluetooth.
FUNC: This layer is for function keys, modifiers, and for changing the default base layer : MAC/EMACS/WINLIN
G_NUM: This is a generic number layer that _might_ be needed because a user may want to jump to a number layer while in a layer that doesn't support momentary activation to a lower layer. This may not be needed for ZMK, but definitely needed for QMK. 
