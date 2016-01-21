# ColorMake

ColorMake colorizes build output, highlighting errors and warnings so you can
notice them more easily. It works with Make, GCC, Clang and other programs with
similar output format. ColorMake is implemented in Bash and requires a terminal
with support for ANSI escape sequences.

![Screenshot](https://github.com/renatosilva/colormake/raw/master/colormake.png)

## Usage

Just call colormake instead of make, passing the arguments as usual. You can
also configure bash aliases, as well as colorize output of other programs:

```bash
alias make='colormake'
alias gcc='COLORMAKE_COMMAND=gcc colormake'
alias clang='COLORMAKE_COMMAND=clang colormake'
```

## License and copyright

Copyright (c) 2014 Renato Silva.
Licensed under the terms of the [3-clause BSD license](LICENSE).
