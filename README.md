# app-snap

I use keyboard chords (via Mate Desktop's Keyboard Shortcuts app) to position app windows.

For example:

    Shift+Mod4+Left
    # ... maps to ...
    app-snap left

    Mod4+Right
    # ... maps to ...
    app-snap right 1/2

    Mod4+Up
    # ... maps to ...
    app-snap center 2/3

`display-deets` is the script that retrieves details needed by `app-snap`. `display-deets` gets details about all the connected displays.

I have plans to add a chord for moving the active window to different displays.

More details to come ...