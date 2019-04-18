# Agents.jl Documentation

Agents.jl is a [Julia](https://julialang.org/) framework for an agent-based modeling (ABM). It provides a structure and components for quickly implementing agent-based models, run them in batch, collect data, and visualize them. To that end, it provides the following functionalities: 

* Default grids to run the simulation, including simple or toroidal 1D grids, simple or toroidal regular rectangular and triangular 2D grids, and simple or toroidal regular cubic 3D grids with von Neumann or Moore neighborhoods. More space structure are to be implemented include arbitrary random networks.
* Running the simulations in parallel on multiple cores or on clusters. (This is not ready yet)
* Automatic data collection in a `DataFrame` at desired intervals.
* Exploring the simulation results interactively in [Data Voyegar 2](https://github.com/vega/voyager).
* Batch running and batch data collection
* Visualize agent distributions on grids

Julia is a language that is especially suitable for ABMs, because a) [it runs fast](https://julialang.org/benchmarks/), b) it is easy to express your ideas in and quick to write, and c) it has rich and easy-to-use packages for data analysis.

Agents.jl is lightweight and modular. It has a short learning curve, and allows one to extend its capabilities and express complicated modeling scenarios. Agents.jl is inspired by [Mesa](https://github.com/projectmesa/mesa) framework for Python.

For a quick tutorial see the example models.

## Installation

Currently, the package is not added to Julia's package list, therefore, install it using this command:

```julia
]add https://github.com/kavir1698/Agents.jl.git
```

## Table of contents

```@contents
```

This is still work in progress. I am working on the following:

* Adding more unit tests
* Implementing more examples
* Parallel computing of batch simulations
* 3D visualization