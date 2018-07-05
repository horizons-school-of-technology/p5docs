# JavaScript Math Functions

 * [`Math.random()`](js/math.md#mathrandom)
 * [`Math.sqrt()`](js/math.md#mathsqrt)
 * [`Math.pow()`](js/math.md#mathpow)
 * [`Math.sin()`](js/math.md#mathsin)
 * [`Math.cos()`](js/math.md#mathcos)

-----

## `Math.sin()`

Usage:

```
Math.sin(angle)

Math.sin(0)            // 0
Math.sin(1)            // 0.8414709848078965
Math.sin(Math.PI / 2)  // 1
Math.sin(2)            // 0.9092974268256817
Math.sin(Math.PI)      // 0
Math.sin(4)            // -0.7568024953079282
```

Parameters:

 - `angle`: an angle measured in radians

Returns:

 - The sine of `angle`

Description:

`Math.sin(angle)` calculates the sine of an angle: a number between -1 and 1
representing the ratio of the vertical side of a right triangle at that angle
to the hypotenuse of that right triangle.

The sine function oscillates from -1 to 1 in a wave, and is useful to use
to calculate the position of something that is oscillating, like a weight
on a soft spring, or a swinging game obstacle.

Wikipedia has more information on [sine](https://en.wikipedia.org/wiki/Sine),
and MDN has more information on
[`Math.sin`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sin)


-----

## `Math.cos()`

Usage:

```
Math.cos(angle)

Math.cos(0)            // 1
Math.cos(1)            // 0.5403023058681398
Math.cos(Math.PI / 2)  // 0
Math.cos(2)            // -0.4161468365471424
Math.cos(Math.PI)      // -1
Math.cos(4)            // -0.6536436208636119
```

Parameters:

 - `angle`: an angle measured in radians

Returns:

 - The cosine of `angle`

Description:

`Math.cos(angle)` calculates the cosine of an angle: a number between -1 and 1
representing the ratio of the horizontal side of a right triangle at that angle
to the hypotenuse of that right triangle.

The cosine function oscillates from 1 to 0 to -1 and back in a wave, and is
useful to use to calculate the position of something that is oscillating, like
a weight on a soft spring, or a swinging game obstacle.

Wikipedia has more information on [cosine](https://en.wikipedia.org/wiki/Cosine),
and MDN has more information on
[`Math.cos`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/sin)


-----


