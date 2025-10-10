JSON to C:\
qmk json2c <json keymap> > <output file>.c

C to UF2 (with rp2040 convert):\
qmk compile -kb ferris/sweep -km <location of C> -e CONVERT_TO=rp2040
