
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
* Fn + 1 or 2 or 3 : hold for 3 seconds to pair that profile, BT light will fast blink
* Fn + 1 or 2 or 3 : quick click, change profile, light will stay on for 5 seconds if connection is successful
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



### _**Additional Notes**_
If your keyboard is plum87 or plum108, go visit this link.  \
http://randombits.me/?p=155


### **Acknowledgements**
Many thanks to kschang on reddit for the translation.  \
https://www.reddit.com/r/MechanicalKeyboards/comments/76pudv/can_anyone_translate_the_manual_for_the_plum_84