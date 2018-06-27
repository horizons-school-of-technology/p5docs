# p5.js Drawing Functions

 * [`game.background()`](p5/drawing.md#gamebackground)
 * [`game.fill()`](p5/drawing.md#gamefill)
 * [`game.stroke()`](p5/drawing.md#gamefill)
 * [`game.line()`](p5/drawing.md#gameline)
 * [`game.rect()`](p5/drawing.md#gamerect)
 * [`game.ellipse()`](p5/drawing.md#gameellipse)
 * [`game.textSize()`](p5/drawing.md#gametextsize)
 * [`game.text()`](p5/drawing.md#gametext)

-----


## `game.background()`

Usage:

```javascript
game.background(red, green, blue);
game.fill(200, 200, 255);  // light blue
```

Parameters:

 - `red`: The red component of the color of the background (0 to 255)
 - `green`: The green component of the color of the background (0 to 255)
 - `blue`: The blue component of the color of the background (0 to 255)

Description:

Colour the whole game screen a single colour, the combination of `red`,
`green`, and `blue` colour components.

For detailed documentation, see:
[p5.js background reference](https://p5js.org/reference/#/p5/background)


-----


## `game.fill()`

Usage:

```javascript
game.fill(red, green, blue);
game.fill(255, 0, 0);
```

Parameters:

 - `red`: The red component of the color (0 to 255)
 - `green`: The green component of the color (0 to 255)
 - `blue`: The blue component of the color (0 to 255)

Description:

Sets the fill colour for shapes drawn after this command.
`red`, `green`, and `blue` parameters each represent a component of
the colour, and are combined to create the colour for filling
shapes drawn after this function is called.

For detailed documentation, see:
[p5.js fill reference](https://p5js.org/reference/#/p5/fill)


-----


## `game.stroke()`

Usage:

```javascript
game.stroke(red, green, blue);
game.stroke(255, 0, 0);
```

Parameters:

 - `red`: The red component of the color (0 to 255)
 - `green`: The green component of the color (0 to 255)
 - `blue`: The blue component of the color (0 to 255)

Description:

Sets the stroke (edge) colour for shapes drawn after this command.
`red`, `green`, and `blue` parameters each represent a component of
the colour, and are combined to create the colour for the outline of
shapes drawn after this function is called.

For detailed documentation, see:
[p5.js stroke reference](https://p5js.org/reference/#/p5/stroke)


-----


## `game.line()`

Usage:

```javascript
game.line(x1, y1, x2, y2);
game.line(100, 100, 200, 100);
```

Parameters:

 - `x1`: the x-coordinate of the start of the line
 - `y1`: the y-coordinate of the start of the line
 - `x2`: the x-coordinate of the end of the line
 - `y2`: the y-coordinate of the end of the line
 
Description:

Draws a line from (`x1`, `y1`) to (`x2`, `y2`) using the current
[stroke](#gamestroke) colour.

For detailed documentation, see:
[p5.js line reference](https://p5js.org/reference/#/p5/line)


-----


## `game.rect()`

Usage:

```javascript
game.rect(x, y, width, height);
game.rect(100, 100, 50, 50);
```

Parameters:

 - `x`: the x-coordinate of the top-left corner of the rectangle
 - `y`: the y-coordinate of the top-left corner of the rectangle
 - `width`: the width of the rectangle
 - `height`: the height of the rectangle
 
Description:

Draws a rectangle with the top-left corner at `x, y`, a width of `width`,
and a height of `height`.

For detailed documentation, see:
[p5.js rect reference](https://p5js.org/reference/#/p5/rect)


-----


## `game.ellipse()`

Usage:

```javascript
game.ellipse(x, y, width, height);
game.ellipse(100, 100, 50, 50);
```

Parameters:

 - `x`: the x-coordinate of the centre of the ellipse
 - `y`: the y-coordinate of the centre of the ellipse
 - `width`: the width of the ellipse
 - `height`: the height of the ellipse
 
Description:

Draws an ellipse (an elongated circle) centered at `x, y` with a width of `width`
and a height of `height`.

For detailed documentation, see:
[p5.js ellipse reference](https://p5js.org/reference/#/p5/ellipse)


-----
