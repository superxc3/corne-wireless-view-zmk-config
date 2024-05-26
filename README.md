# Mousekey repo for Corne Niceview
You are directed from https://github.com/superxc3/zmk-config-crkbd/blob/master/README.md

![653859b0ac95101fba23d6955b0ee6d](https://github.com/superxc3/corne-wireless-view-zmk-config/assets/79617315/0749c972-ad3a-4e4f-8522-117d4ab5363f)


1. This branch for `niceview` display.
2. Quick link to [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/).
3. This mouse repo seems not compatible with nickcoutsos's web keyremap anymore. You have to edit the keycodes in keymap.c instead of relying on nickcoutsos. Check [Codes](https://zmk.dev/docs/codes) for a full list of zmk keycode, you may read other interesting function in the same page.


### Keycodes for mouse-native-repo
You have to edit `keymap.c`. 

| Mouse Function   | Keycode in corne.keymap |
|------------------|-------------------------|
| Mouse Button 1   | `&mkp MB1`              |
| Mouse Button 2   | `&mkp MB2`              |
| Mouse Button 3   | `&mkp MB3`              |
| Move Cursor Up   | `&mmv MOVE_UP`          |
| Move Cursor Down | `&mmv MOVE_DOWN`        |
| Move Cursor Left | `&mmv MOVE_LEFT`        |
| Move Cursor Right| `&mmv MOVE_RIGHT`       |
| Mouse Scroll Up  | `&msc SCROLL_UP`        |
| Mouse Scroll Down| `&msc SCROLL_DOWN`      |
| Mouse Scroll Left| `&msc SCROLL_LEFT`      |
| Mouse Scroll Right| `&msc SCROLL_RIGHT`    |

[Source](https://github.com/urob/zmk-config/blob/upstream-mouse/config/mouse.dtsi)
