# SBGN2ODE
A set of tools for converting Ordinary Differential Equation (ODE)-based dynamic models from [Systems Biology Graphical Notation (SBGN)](https://sbgn.github.io/) to ODE systems in LaTeX equations and/or in Julia symbolic expressions.

## Tools

`sbgn2tex`: Receives an SBGN file containing a dynamic model and outputs its ODE system in LaTeX equations (using the align environment).

`sbgn2jl`: Receives an SBGN file containing a dynamic model and outputs its ODE system in symbolic expressions of Julia programming language.

`jl2tex`: Receives a Julia file containing an ODE system and outputs its ODE-system in in LaTeX equations (using the align environment).
