# Grids.jl

The purpose of Grids.jl will be to define efficient types for holding Grids. The
types of functions that this will handle are familiar things like `linspace`,
`meshgrid`, `ndgrid`. Key features will be:

- These functions will return low-memory iterator types
- Be able to be `collect()`ed into standard arrays
- Support n-d grids

And more. Join the Roadmap discussion for more details.
