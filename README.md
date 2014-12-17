Slow maps

![](http://www.snail-world.com/wp-content/uploads/snail-front.jpg)

It's 2015 and slow maps are rarer and more tasty than ever. Never before has the hand crafted slow map been more alluring. If all your yaks are shaved and all your ducks are in a row then it's time to crank the oven and bake a beautiful slow map.

Here are some tips:

### Data prep

1. Before tiling your data union every geometry in your dataset into a single feature so that the extent of your unioned geometry is the same as your entire dataset. This will ensure that this spatial indexes are useless and this feature has to be processed completely for every tile you cut.


### Graphics programming

1. Write a hardware accelerated rendering pipeline and run it with a software rasterizer so that you use the CPU and all calls are translated at runtime.


### Benchmarking

1. Write a benchmark that profiles the startup time of your program instead of profiling your program in use. Then optimize the shit out of it. To do this you might consider moving rarely used data structures to globals so they compiler can initialize then right away statically. If you hit crashes don't worry just keep optimizing.



1. More to come (TODO: harvest any still relevant ideas from [2014](https://github.com/IvanSanchez/slides-slow-maps) and [2011](http://dbsgeo.com/foss4g2011/foss4g2011-lecture2-how-to-make-slow-maps.pdf).

