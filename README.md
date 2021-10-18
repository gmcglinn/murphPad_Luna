# murphPad_Luna

Originally designed by HellSingCoder for use on a Sofle, ported over to work on a vertically oriented MurphPad OLED. 

Reduced functionality and size of the Luna icons and animations to fit on the Pro-Micro that comes with the stock MurphPad kit.


Keymaps are as follows:

```
[_BASE] = LAYOUT(
        KC_DELETE,   KC_PSCREEN,   KC_PAUSE,   KC_CALCULATOR,
	KC_NLCK, KC_PSLS, KC_PAST, KC_PMNS,
        KC_P7,   KC_P8,   KC_P9,   KC_PPLS,
        KC_MEDIA_PLAY_PAUSE,  KC_P4,   KC_P5,   KC_P6,   _______,
        KC_LSHIFT, KC_P1,   KC_P2,   KC_P3,   KC_PENT,
        MO(_FN1),  KC_P0,   _______, KC_PDOT, _______,

                  _______, _______, _______

    ),
    [_FN1] = LAYOUT(
                 _______,  _______, _______, _______,
                 _______,  _______, _______, _______,
                 _______,  KC_UP, _______, KC_CAPSLOCK,
        _______, KC_LEFT, KC_DOWN, KC_RIGHT, _______,
        _______, KC_SNEAK,  KC_BARK, KC_JUMP, _______,
        _______, _______,  _______, _______, _______,

                 _______, _______, _______

    )
};
```

Since this is self-contained to the Murphpad I gave a bit of leniency to the WPM counter so we could get Luna running quicker and for longer so you can enjoy the animations.
Also because this is a keypad and not a keyboard with space, control, etc I have added the triggers for Luna's separate actions on the Navigational layer of the MurphPad (found by holding MO(_FN1)) on Numpad Keys 1, 2, and 3. 

Display also contains a Function Layer indicator, Capslock and Numlock indicators, and an innacurate WPM counter for keypad presses



Find the original code by HellSingCoder for a Sofle here: https://github.com/HellSingCoder/qmk_firmware/tree/master/keyboards/sofle/keymaps/helltm
