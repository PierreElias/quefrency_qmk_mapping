# quefrency_qmk_mapping
For flashing a quefrency rev2 to allow for the rotary encoder knob to work as volume up/down

Follow directions here 
https://www.reddit.com/r/MechanicalKeyboards/comments/8ct02i/macos_quick_start_guide_for_flashing_kbd75/?st=JKF0BDVY&sh=aca1db0b

except do the following:

1. Replace the files in qmk_firmware/keyboards/keebio/quefrency/keymaps/via with the ones posted in this repo
2. Instead of using the kbd75 make code designated in the above post, use "make keebio/quefrency/rev2:via"

You should then generate a hex file that you can use to flash your board. 

More info about re-flashing the quefrency rev2 can be found here. 

https://www.reddit.com/r/olkb/comments/kag2e9/putting_quefrency_rev2_back_into_dfu_bootloader/
