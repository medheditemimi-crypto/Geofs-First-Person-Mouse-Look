# Geofs-First-Person-Mouse-Look
Ever wanted to look around in geofs without clicking and dragging you cursor?  Well this tampermonkey userscript is for you! 

Features:
- Smooth first-person mouse look
- Pointer Lock mouse control
- Horizontal mouse movement controls yaw
- Vertical mouse movement controls pitch
- Adjustable mouse sensitivity
- Adjustable camera smoothing
- Configurable minimum and maximum pitch
- Optional horizontal and vertical mouse inversion
- Configurable mouse-look toggle key
- Built-in settings window
- No external userscript libraries or addon menus required
- Restores the previous camera mode and orientation when disabled

Controls:
- "I" to enable
- "I" or "Escape" to disable
- "F8" to open the settings menu

Notes:
This userscript only works for cockpit/follow view, if any other view is selected, it automatically reverts to follow view.
When enabled, the mouse gets hidden.

Known bugs:
-Weird behaviour when looking at your seat or looking sideways, if you have a fix/explanation for this, please lmk.
-Smootheness setting may not work for all devices.

Default settings:
Sensitivity:    0.10
Smoothing:      14
Minimum Pitch: -80
Maximum Pitch:  80
Invert X:       Off
Invert Y:       Off
Toggle Key:     I

Installation:
1. Install [Tampermonkey](https://www.tampermonkey.net/).
2. Create a new userscript.
3. Replace the default contents with the script from this repository.
4. Save the script.
5. Open GeoFS.
6. Wait for the game to finish loading.
Greasyfork coming soon!
