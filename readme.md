# Tetris Diagram Editor
This is a slightly modified copy of the tetris diagram editor found at https://fumen.zui.jp/.
I am not the original author but I made this copy so I could use it locally and add some quality of life features to it.

Modifications:
- includes `greyout.js`, `mirror.js` add-ons made by swng.
- `english.js`, `greyout.js`, `mirror.js`, `frame.js`, `listing.js` and `pfcode.js` add-ons are loaded automatically. 
- removed the add-on button and made the addon UI always visible.
- if Auto Output is checked, it will also auto update the pfcode diagram.
- added button for copying pfcode diagram to clipboard.
- the onclose add-on has been turned into a checkbox toggle at the bottom of the page because some people want it while others find it an annoyance.
- fumen urls support starting with `#?` syntax as in `http://example.com/#?v115@vhAAgH`. This allows for sharing much longer fumen urls because it is now character limited by the web browser instead of the server.

If you somehow found this not knowing what it is and you need a guide for how to use the fumen diagram editor, see https://harddrop.com/forums/index.php?topic=4469.0.
The guide is missing an image, which you can find on the web archive here https://web.archive.org/web/20200605163950if_/https://harddrop.com/file/pic/gallery/4148.jpg.