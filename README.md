# mandelbrot-ocaml

One of our first tp at EPITA was to draw some fractals in ocaml. One I'm proud of is mandelbrot. The mandelbrot function allows you to really zoom in the fractal which makes it much more interesting. It works like this : 

```ocaml
mandelbrot [int : degree of prescision] 
[float * float : x and y coords of the bottom left corner]
[float : size (the smaller the size the bigger the zoom)]
```

Enjoy !

I have since made other, better versions in c with [sdl](https://github.com/matthieuporte/mandelbrot-sdl) and with [gtk](https://github.com/matthieuporte/mandelbrot)

