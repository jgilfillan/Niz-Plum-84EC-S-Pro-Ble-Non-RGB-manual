
# 84EC(S) Pro-Ble Keyboard (Non-RGB)
English Translated Manual

_last edit  2018.11.20_

<br>

pull request is always welcome :)

<br>


## 5.1 Modes
Your keyboard has two modes: office, which is fixed, and program, which can be remapped using the KB84 Config program.
To swap modes, Fn + F12/(M) and hold for THREE SECONDS.
The key, which is also the (M) light will stay on, showing you're in program mode.
Do it again to switch back to office mode.

<br>

## 5.2 Hotkeys
* Fn + ⤓ (F9) : APC(Actuation Point Change) mode toggle between low (1 flash of CAPSLOCK)  and high (2 flashes of CAPSLOCK)

    * default = 2.5mm ; low (1 flash) = 2mm ; high (2 flashes) = 3mm
    * When reconnected to pc, it becomes default. (2.5mm)
    * If you have old version of plum84, you need to press “FN + PAGEUP / PAGEDOWN” instead.

* Fn + Win : Lock Windows key
* Fn + Win⇌Alt : swap Windows key and Alt
* Fn + ⥮ (F8) : swap Caps Lock and Ctrl
* Fn + Pause : ScrLock
* Fn + PrScr : NumLock
* Fn + Esc : block NumLock (will also block NumLock from another keyboard)

<br>


## 5.3  Bluetooth functions
* Fn + 1 or 2 or 3 : hold for 3 seconds to pair that profile, BT light will fast blink. Note that if you are trying to pair multiple devices, you must first turn off BT on the previously paired devices before you can pair a new device.
* Fn + 1 or 2 or 3 : quick click, change profile, light will stay on for 5 seconds if connection is successful
* Fn + bluetooth/battery symbol : while the keyboard is connected by USB or charging, use this to toggle between allowing charging or enabling wired/wireless mode.
* Fn + `(~) : swap between Wired vs wireless mode

<br>


## 6.1 Bluetooth Light
* fast blink = pairing mode
* slow blink = connected
* constant on = connected (turns off after 5 seconds)

<br>


## 6.2 Battery light (`(~) key)
* on = charging
* off = charged
* blinking = battery low

<br>


## 6.3 Display light intensity
* Fn + ↑/↓ : 4 levels of intensity

<br>


## 7.0 Please use a 2A USB charger for best charging speed

<br>



## 8.0 Factory reset the board

hold down ALL FOUR CORNER KEYS (Esc, Ctrl(Left), →, Delete) for 5 seconds

<br>
## These instructions appear on my newer version of the instructions (maybe a newer version of the keyboard as well). They may not apply to older versions of the keyboard.
* The left fn and right fn keys can be programmed separately in program mode and map to different layers.
* Press left and right fn at the same time for 3 seconds to swap the regular keys with their fn versions. Based on which fn you press first you toggle right-fn-lock or left-fn-lock. 2 flashes = left fn active, 3 flashes = right fn active, 1 flash = disabled
* Fn + clock with A symbol : press this to cycle the key repeat delay among 500, 300, 100 ms. The number of flashes indicates which mode is active; default first one; this preference is reset on restart.
* Fn + AA symbol : press this to cycle between key repeat speed among 1x, 2x, 4x, 8x. The number of flashes indicates which mode is active; defaults to first one; preference is reset on restart. In the USB/Bluetooth mode, the speed will only be 1x, and this setting is invalid.
* Fn + \ : press and hold for 3 seconds to swap Backspace and the \ key. Persisted across restarts.
* Fn + mouse symbols : simulate mouse movement and mouse clicks
* Fn + mouse with clock : cycle between 8/6/4/2 ms time interval per mouse movement
* Fn + Px mouse : cycle between each mouse movement moving 2/3/4/5 pixels
* Fn + Y for 3 seconds when USB is not connected will show the current battery level by lighting up 1-4 of the F9-F12 keys (1 is low battery and all 4 is full battery).
* Fn + T for 5 seconds lets you cycle between 1 hour/2 hour/3 hour for automatic shutoff when in wireless mode. Default is 3 hours.

# Extra

## 9. For MacOS user who often use F1 - F12
 *  If you are using MacOS, Fn + F1 – F12 would not work as you expected.
ksmigrod explanied the reason for the problem in reddit. \
  “On Linux in Bluetooth mode this keyboard is supported by Apple keyboard driver. This driver tries to mimic Apple keyboard behaviour and does conversion from function key (F1-F12) to media key codes on the fly. NiZ keyboard does not send any codes for its function key, so Linux's keyboard driver cannot map Fn+F1 to F1.” \
 https://www.reddit.com/r/MechanicalKeyboards/comments/6yieo6/review_plum_84_35g_bluetooth_nonrgb/

Though he explained the solution for Linux OS, it seems his solution doesn't apply to MacOS. \
Instead, I suggest you to toggle following macOS option as you want.  \
(System Preferences > Keyboard > Use F1, F2, etc. keys are standard function keys …) 

<br>


## 10. KBD84 software
When using the KBD84 software to program the keyboard, be sure to select ReadAll first.  This reads the current keyboard mappings from the keyboard.  If you don’t select ReadAll first, you will be essentially starting with blank mappings and you will need to map every single key.

<br>


## 11. Calibration with key not working
Source : Software > CalibrationiLite > CalibrationLite.exe

(This program only support Windows OS)

Video link : http://v.youku.com/v_show/id_XMzQxMjg5MzA0NA==.html?x&sharefrom=android&sharekey=b64f9bbcfb7ce67d6be729c0b98844d92 \
(Open the link in mobile phone)

1. Press 'ReadVersion' \
(※ If you switch Win key and Alt key, the error message('Keyboard disconnect') will appear)


2. Press 'InitialCalib' \
(After 2-3 seconds, InitialCalib will finish)


3. (With pressing the key not working) Press 'PressCalib' \
(Calibration is finished when 'Press Key Calibration Finished' shows up)


4. (With pressing the key not working) Close the software


5. Release the the key not working. Reconnect the keyboard, and check the key

<br>

(※ Try several times with the solution above. If key is not working after the trial, pressing the key not working from the second step of solutions)

<br>


## 12. Software errors out with the message "Keyboard is not connected!" when starting up
Do a factory reset of the board and try again. I have found that the software won't work if you have used the ``Fn + Win⇌Alt : swap Windows key and Alt`` function, and possibly the other ``Fn + ...`` functionalities as well.

<br>


### _**Additional Notes**_
If your keyboard is plum87 or plum108, go visit this link.  \
http://randombits.me/?p=155

<br>


### **Acknowledgements**
Many thanks to kschang on reddit for the translation.  \
https://www.reddit.com/r/MechanicalKeyboards/comments/76pudv/can_anyone_translate_the_manual_for_the_plum_84

<br>


