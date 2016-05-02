## Requirements ##

* Python 3
* [pyautogui](http://pyautogui.readthedocs.io/en/latest/install.html): module for programmatically controlling the mouse and keyboard
* [RPi.GPIO](https://sourceforge.net/p/raspberry-gpio-python/wiki/install/): installed by default in Raspbian.

### Troubleshooting ###

**Xlib.error.DisplayNameError: Bad display name ""**

If you are using SSH, try install using a session running totally in the device.

**ImportError: No module named pyautogui**

run scripts using `python3`

