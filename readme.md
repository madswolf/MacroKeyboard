## install
1. install qmk msys
2. install qmk toolbox

## build
clone repo into qmk\qmk_firmware\keyboards
rename to gamingrevengeance, for some reason having the holder named MacroKeyboard does not work
run the command in qmk msys:
´´qmk compile -kb gamingrevengeance -km defaul´´

## flash
open qmk toolbox
tic "autoflash"
open the built firmware in qmk\qmk_firmware\keyboards\gamingrevengeance_default.hex
short gnd and reset on keyboard
wait for the flash to finish

## Enjoy gaming