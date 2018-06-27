# p5.js Drawing Functions

-----

## `game.fill()`

Syntax:

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
[p5.js ellipse reference](https://p5js.org/reference/#/p5/fill)

-----

## `game.ellipse()`

Syntax:

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
