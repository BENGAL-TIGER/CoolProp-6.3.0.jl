

# CoolProp.jl
A Julia wrapper for CoolProp (http://www.coolprop.org)

This repo was forked from [CoolProp/CoolProp.jl](https://github.com/CoolProp/CoolProp.jl) to lock the package to CoolProp v6.3.0 for Linux installations. Linux shared libraries are not available beyond CoolProp v6.3.0, so normal installations fail. macOS and Windows installations can install CoolProp/CoolProp.jl trouble-free.

## Installation

Linux:

```julia
pkg> add https://github.com/BENGAL-TIGER/CoolProp-6.3.0.jl.git
```

or

```julia
julia> Pkg.add(url="https://github.com/BENGAL-TIGER/CoolProp-6.3.0.jl.git");
```

----
    
macOS, Win:

```julia
pkg> add https://github.com/CoolProp/CoolProp.jl.git
```

or

```julia
julia> Pkg.add(url="https://github.com/CoolProp/CoolProp.jl.git");
```

