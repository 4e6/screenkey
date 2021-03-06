screenkey 0.6.2
---------------

- HiDPI support
- Fix initial state of "Persistent window" in the preferences.
- Allow to reset the stored the geometry from the preferences also when
  changed interactively.


screenkey 0.6.1
---------------

- Fix exception on first run.


screenkey 0.6
-------------

- The ``python-xlib`` module and the ``xmodmap`` executable are not
  required/used anymore. screenkey now uses ``libX11.so.6`` directly.
- Key composition/input method support.
- A new setting (always show Shift) has been added to always add "Shift" in
  modifier sequences which contain capitalizable letters.
- CapsLock and NumLock status (on/off) is now shown when pressed.


screenkey 0.5
-------------

- Fixes issues with recent ``glib`` versions.
- ``XAUTHORITY`` is no longer required to be set.


screenkey 0.4
-------------

- The font is now configurable as well
- Tweaks to symbol spacing
- Highlight recent keypresses for improved readability


screenkey 0.3
-------------

- Multi-monitor support
- Configurable size/position
- Can show modifier sequences only
- Improved backspace processing (3 different modes)
- Normal/Emacs/Mac caps modes
- Enable/disable dynamically by pressing both control keys
- All settings available through command-line flags
- Usable without system tray (for tiling window managers)
- Several bug fixes
