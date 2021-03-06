Markdown File of usefull MacOS commands
---

### Clear Quarantine on File aka. "Unable to open file due to unauthorised developer". 
```
xattr -r -d *quarantine name* *file path*
```
- com.apple.quarantine
- Xattr is Extended Attributes, it is used to modify attributes of a file.
- This is useful in this situation, where -r will select all quarantine attributes, and -d will delete the selected (typed) attribute. 
---

### SMC reset
1. Shut down the computer.
2. On the left side of the keyboard, press and hold the Shift, Control, and Option keys while simultaneously holding the power button.
3. After 10 seconds, release all of the keys.
4. Turn on MacBook.

- Computer's fan is running too loud/often even with low memory usage.
- Battery drains at an abnormally fast rate.
- Computer's performance is sluggish.
- Laptop's trackpad won't function correctly.
- Unable to connect to any wireless networks.
- Computer shuts down at a slow rate.

### PRAM reset
1. Shut down the computer.
2. Press the power button.
3. Immediately after, press Command, Option, P, and R all at the same time on the keyboard.
4. Hold these keys down until you hear the Mac's startup sound for a second time.
5. Release all of the keys.

- Erratic volume behavior.
- Issues with keyboard response.
- Wrong time zone/clock information.
- Mouse scrolling/clicking issues.
- Display and resolution settings change on their own or don't function properly.
