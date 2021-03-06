![Makie.jl](assets/logo.png)

## Welcome to Makie!

[`Makie`](https://github.com/JuliaPlots/Makie.jl/) is a high-performance, extendable, and multi-platform plotting ecosystem for the [Julia](https://julialang.org/) programming language.

## Installation and Import

```julia
]add Makie
using Makie
```

`Makie.jl` bundles `AbstractPlotting.jl` and the `GLMakie.jl` backend.
If you want to use a different backend like `CairoMakie`, add and import `AbstractPlotting` as well:

```julia
]add AbstractPlotting, CairoMakie
using AbstractPlotting
using CairoMakie

CairoMakie.activate!() # only if a different backend is active already
```

## First Steps

- Learn the basics of plotting with Makie in the [Tutorial](@ref)
- Check out how to make more complex plots and layouts in the [MakieLayout Tutorial](@ref)
- See example plots in the [gallery](http://juliaplots.org/MakieReferenceImages/gallery/index.html).


## Makie Ecosystem

| Package | Description |
| :-- | :-- |
| [`AbstractPlotting.jl`](https://github.com/JuliaPlots/AbstractPlotting.jl) | Defines all infrastructure objects which can be visualized using one of the three backend packages. |
| [`GLMakie.jl`](https://github.com/JuliaPlots/GLMakie.jl) | Default Makie backend. GPU-powered, interactive 2D and 3D plotting in standalone `GLFW.jl` windows. |
| [`CairoMakie.jl`](https://github.com/JuliaPlots/CairoMakie.jl) | `Cairo.jl` based, non-interactive 2D backend for publication-quality vector graphics. |
| [`WGLMakie.jl`](https://github.com/JuliaPlots/WGLMakie.jl) | WebGL-based interactive 2D and 3D plotting that runs within browsers.


### Extension Packages

| Package | Description |
| :-- | :-- |
| [`AlgebraOfGraphics.jl`](https://github.com/JuliaPlots/AlgebraOfGraphics.jl/) | Grammar-of-graphics style plotting, inspired by ggplot2. |
| [`GeoMakie.jl`](https://github.com/JuliaPlots/GeoMakie.jl) | Geographic plotting utilities. |


## Getting Help

1) Use the REPL `?` help mode
1) Join the `#makie` channel in the [Julia Slack group](https://slackinvite.julialang.org).
1) Open an issue in the [Makie.jl](https://github.com/JuliaPlots/Makie.jl) repository.
