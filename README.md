
## My shop keyboard-hoarders.com and keyboardhoarders.etsy.com -

![lily](https://github.com/user-attachments/assets/41c643e3-44f1-4863-9274-2a0181e748f5)

# Flashing firmware:
1.Leave both halves powered on.

2.Plug in right half via USB to computer.  > Press the reset button on the inner halves twice quickly to put into bootloader mode. > Drag and drop the settings_reset file into the directory NICENANO. > After transfer you may get an error and you can ignore and move on to next step. > Unplug right half

3.Plug in left half and follow step one to put into bootloader and drag and drop settings-reset file. > after transfer leave left plugged in. 

4.With left still plugged in put into bootloader again > drag and drop lily-left firmware into directory. > unplug left half.

5.Plug in right half and follow step 3 but this time drag and drop lily58-right firmware.

6.After this your done.  You will need to go into your computers bluetooth device history and remove your old pairing on Lily58 and pair it as a new device.

# keymap

<img width="984" height="1918" alt="my_keymap-15" src="https://github.com/user-attachments/assets/24403627-767e-4d4b-b059-afee95e613e0" />



# Bluetooth
ZMK uses secure bluetooth profiles.  This means only one device per profile.  If you run into bluetooth issues I recommend wiping the stored profiles with BT_CLR_ALL button combo thats found on the lower layer.  If you want to flash your own firmware I have a guide on my website over at https://keyboard-hoarders.com/pages/guides-1
