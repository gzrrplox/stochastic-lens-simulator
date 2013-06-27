Stochastic Lens Simulator by Gzrrplox
=====================================

My first 4k intro, made for [Instanssi 2011](http://instanssi.org/arkisto/event/1/).

This was mainly an attempt at [Reyes](http://dx.doi.org/10.1145/37402.37414)-style 
[stochastic rasterization](http://dx.doi.org/10.1145/964965.808590) with a GPU.
End result first generates motion paths with a vertex shader, then continues
to extracting bounding polygons with a geometry shader and finally does simple stochastic point sampling
with a fragment shader. The huge and noisy image is downscaled for display with a 
separable gaussian filter in two passes.

Noises are also generated with GLSL.

- [Pouet](http://pouet.net/prod.php?which=56990)
- [Youtube](http://www.youtube.com/watch?v=QLhrBact-Mk)
- License: BSD3
