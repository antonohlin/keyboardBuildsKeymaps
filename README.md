#### JSON to C:  
`qmk json2c <json keymap> > <output file>.c`

#### C to UF2 (with rp2040 convert):  
`qmk compile -kb <location of keyboard in qmk> -km <location of keymap.c> -e CONVERT_TO=rp2040_ce`

#### lily example:  
`qmk compile -kb mechboards/lily58/pro -km lilyFerris -e CONVERT_TO=RP2040_ce`  
keyboard path: `qmk_firmware/keyboards/mechboards/lily58/pro`  
keymap path: `qmk_firmware/keyboards/mechboards/lily58/pro/keymaps`
