# p5.js User Input Functions

 * [`game.keyIsDown()`](#gamekeyisdown)
 * [`game.mouseIsPressed`](#mouseispressed)
 * [`game.mouseX`](#mousex)
 * [`game.mouseY`](#mousey)

-----


## `game.keyIsDown()`

Usage:

```javascript
game.keyIsDown(key) // returns true or false

if (game.keyIsDown('w')) {
  // do something when the W key is pressed
}
if (game.keyIsDown('left')) {
  // do something when the left arrow key is pressed
}
```

Parameters:

 - `key`: a string or number representing a key (see description)

Returns:

 - `true` if the key is currently pressed
 - `false` if the key is not currently pressed

Description:

Detects whether a specified key is currently down or not, and returns
a boolean (true or false) indicating whether the key is down.

The `key` parameter may be one of three things:

 * A single-character string representing a key on the keyboard:

    * 'a'
    * 'B'
    * '1'
    * '='
    * …

 * A string name of a special key:

    * 'alt'
    * 'backspace'
    * 'control'
    * 'delete'
    * 'down'
    * 'enter'
    * 'escape'
    * 'left'
    * 'option'
    * 'return'
    * 'right'
    * 'shift'
    * 'tab'
    * 'up'
    * 'space'

 * A keycode: a number representing a keyboard key. Visit
   [http://keycode.info/](keycode.info) to find keycodes of keys on your
   keyboard.

-----


