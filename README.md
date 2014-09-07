# ColorMake

ColorMake will colorize output of Make and GCC, highlighting errors and warnings
so you can notice them more easily. ColorMake is implemented in Bash and
requires a terminal with support for ANSI escape sequences.

![Screenshot](https://raw.githubusercontent.com/renatosilva/colormake/master/colormake.png)

## Usage

Just use the script instead of make, passing the arguments as usual. You can
also have `make` aliased to `colormake` for instance. Just make sure to not
rename it to `make` as that would cause recursive calls.

## License and copyright

Copyright (c) 2014 Renato Silva.
Licensed under the terms of the GNU GPL version 2.
