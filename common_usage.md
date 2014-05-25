Below are a series of examples of common operations in Julia. They assume you already have Julia installed and working
(the examples are currently tested with Julia v0.3 - latest).
 
### Hello World
 
The simplest possible script.
 
{{ code_file('hello_world.jl') }} 

### Simple Functions

The example below shows two simple functions, how to call them and print the results. Further examples of number formatting are shown below.

{{ code_file('functions.jl') }} 

### Strings Basics

Collection of different string examples (string indexing is the same as array indexing: see below).

{{ code_file('strings_basics.jl') }} 

### String: Converting and formatting

{{ code_file('formatting_converting_strings.jl') }} 

### String Manipulations

{{ code_file('string_manipulation.jl') }} 

### Arrays

{{ code_file('arrays.jl') }} 

### Dictionaries

Julia uses [Dicts](http://docs.julialang.org/en/latest/stdlib/base/#associative-collections) as associative collections. Usage is very like python except for the rather odd `=>` definition syntax.

{{ code_file('dicts.jl') }} 

### Loops and Map

[For loops](http://julia.readthedocs.org/en/latest/manual/control-flow/#repeated-evaluation-loops) can be defined in a number of ways.

{{ code_file('loops_map.jl') }}

### Types

Types are a key way of structuring data within Julia

{{ code_file('types.jl')}}

### Plotting

Plotting in Julia is only possible with additional Packages. Examples of different packages are given below.

#### PyPlot

[PyPlot Package Page](https://github.com/stevengj/PyPlot.jl).

PyPlot needs Python and matplotlib installed [matplotlib.pyplot docs](http://matplotlib.org/api/pyplot_api.html).

{{ code_file('pyplot.jl') }}

{{ source_image('pyplot.png') }}

#### Winston

[Winston Package Page](https://github.com/nolta/Winston.jl)

Matlab-like plotting. Installed via `Pkg.add("Winston")`

{{ code_file('winston.jl') }}

{{ source_image('winston.svg') }}

#### Gadfly

[Gadfly Package Page](https://github.com/dcjones/Gadfly.jl)

ggplot2-like plotting. Installed via `Pkg.add("Gadfly")`

{{ code_file('gadfly.jl') }}

{{ source_image('gadfly.png') }}

### Error Handling

{{ code_file('error_handling.jl') }}