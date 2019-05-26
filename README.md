## Welcome to the Advanced Numerical Analysis repository, edited by Alberto Chiusole

Repo for the Advanced Numerical Analysis course @ University of Trieste, containing mainly exercises.
During the course, held by [prof. Paolo Novati](http://www.novati.dmg.units.it/), we investigated different numerical methods to perform approximations.

The following list collects the exercises done so far:

1. [Interpolation using Chebyshev nodes](http://devzero.tk/advanced-numerical-analysis/exercises/01_interpolation_with_cheby.html), using "canonical" polynomial interpolation, Lagrange interpolation and Newton method (not working).

1. [Newton-Cotes quadrature formula for integration](http://devzero.tk/advanced-numerical-analysis/exercises/02_quadratures_with_newton_cotes.html), using Chebyshev nodes.


As final project, an adaptive integration method using Cavalieri-Simpson's interpolation rule was developed, and is available at:

1. [Adaptive numerical integration with Cavalieri-Simpson method](http://devzero.tk/advanced-numerical-analysis/exercises/project_adaptive-integration.html).


To install the Python libraries required, on Linux, use the `pip` package manager:
```
$ pip install jupyterlab
```

or install the same dependencies used to develop, using the file `requirements.txt`, with:
```
$ pip install -r /path/to/this/repo/requirements.txt
```
or using the latest requirements file available in this repo, downloaded from the net:
```
$ pip install -r <(curl https://raw.githubusercontent.com/bebosudo/advanced-numerical-analysis/master/requirements.txt)
```
