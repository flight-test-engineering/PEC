This repository contains the notebooks featured in the International Standard Atmosphere (PEC/ISA) youtube mini-series.

The channel's homepage is [flighttestengineering](https://www.youtube.com/@flighttestengineering)

The mini-series has 3 parts:

* Part 1: [plotting data video](https://youtu.be/79wntFb6wkc) from atmospheric sounding radiosonde - this includes a journey into large datasets plotting with [datashader](https://datashader.org/).
* Part 2: [deriving the equations video](https://youtu.be/RA9O5DRcWtA) for the International Standard Atmosphere - including a small introduction to [sympy](https://www.sympy.org/en/index.html)
* Part 3: [coding the equations in python video](https://youtu.be/TZJ3B89REHw), with stand-alone functions and on a module that can be easily imported into other notebooks

The associated notebooks are in this repo.

To install the ISA_module, download the wheel file (.whl) and run this command:

```
pip install isa_module-1.0-py3-none-any.whl
```
You can then
```
import ISA_module as ISA
```
and have all the functions available under the "ISA" namespace

Enjoy!
