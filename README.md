# app-snap

```
Usage:
    
    app-snap [POSITION] [SCALAR]
    
    POSITION: left, center, right
    SCALAR: any fraction or floating point number less than 1
    
    e.g.
      app-snap left   1/2
      app-snap right  0.66
      app-snap center 3/4
``` 


I use keyboard chords (via Mate Desktop's Keyboard Shortcuts app) to position app windows.

For example:

    Shift+Mod4+Left
    # ... maps to ...
    app-snap left 1/2

    Mod4+Right
    # ... maps to ...
    app-snap right 1/2

    Mod4+Up
    # ... maps to ...
    app-snap center 2/3

`display-deets` gets details about all the connected displays; these are used by `app-snap` to position the active app window in the respective display.

I have plans to add a chord for moving the active window to different displays.

More details to come ...