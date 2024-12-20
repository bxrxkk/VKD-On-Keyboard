# VKD-On-Keyboard
Vanish-Key-Delay On Keyboard

# NOTE
This is still under developement as i am planning to add this function to the "W" and the "S" keybind

Please use the new versions found in releases

------------------------------------------

* This executable macro allows dynamic switching between 'a'/'A' and 'd'/'D' keys to provide continuous movement in games/work.
* Made by using the software 'AutoHotkey'
* When one key is held and the other is pressed, the macro switches movement to the newly pressed key without the need of the old key being released and the new one being clicked.

Features:

* Continuous Movement: Prevents stopping when both 'a' and 'd' are pressed.
* Priority Switching: Prioritizes the latest key press for a non-delayed direction change.

How It Works:

* Variables: Tracks key states with isAPressed and isDPressed.
Pressing 'a':
If 'd' is pressed, release 'd' and press 'a'.
If 'd' is not pressed, press 'a'.
Pressing 'd':
If 'a' is pressed, release 'a' and press 'd'.
If 'a' is not pressed, press 'd'.
Releasing Keys:
On 'a' release: Stop 'a' and check if 'd' is pressed to continue 'd'.
On 'd' release: Stop 'd' and check if 'a' is pressed to continue 'a'.

Usage:

Run this script with AutoHotkey before playing the game to activate it.

This is mostly designed for gaming where 'a' and 'd' is used for movement.
