# Mandelbrot

[Mandelbrot][link]
[link]: https://sprucewillis.github.io/mandelbrot/

The Mandelbrot set is a fractal generated by iterating over the set of complex numbers.

## Implementation

Images generated are drawn by using an escape time algorithm: pixels represent a coordinate of the form (x + *iy*). Each pixel is assigned a color based on the number of iterations required to exceed an escape threshold, normalized to fit the color scheme and range of iterations required.  

To produce smooth color gradients, iterations are filtered using a potential function; colors are then linearly interpolated from a given palette.
