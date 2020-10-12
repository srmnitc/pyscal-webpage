
# pyscal - python Structural Environment Calculator

complete documentation with examples available
[here](https://pyscal.com/).

**pyscal** is a python module for the calculation of local atomic
structural environments including [Steinhardt\'s bond orientational
order
parameters](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.28.784)
during post-processing of atomistic simulation data. The core
functionality of pyscal is written in C++ with python wrappers using
[pybind11](https://pybind11.readthedocs.io/en/stable/intro.html) which
allows for fast calculations with possibilities for easy expansion in
python.

Steinhardt\'s order parameters are widely used for [identification of
crystal
structures](https://aip.scitation.org/doi/full/10.1063/1.4774084). They
are also used to identify if an atom is [solid or
liquid](https://link.springer.com/chapter/10.1007/b99429). pyscal is
inspired by
[BondOrderAnalysis](https://homepage.univie.ac.at/wolfgang.lechner/bondorderparameter.html)
code, but has since incorporated many additions and modifications.
pyscal module includes the following functionality-

Highlights
----------

-   fast and efficient calculations using C++ and expansion using
    python.
-   calculation of Steinhardt\'s order parameters and their [averaged
    version](https://aip.scitation.org/doi/full/10.1063/1.2977970) and
    [disorder parameters](https://doi.org/10.1063/1.3656762).
-   links with [Voro++](http://math.lbl.gov/voro++/) code, for
    calculation of [Steinhardt parameters weighted using face area of
    Voronoi
    polyhedra](https://aip.scitation.org/doi/full/10.1063/1.4774084).
-   classification of atoms as [solid or
    liquid](https://link.springer.com/chapter/10.1007/b99429).
-   clustering of particles based on a user defined property.
-   methods for calculating radial distribution function, voronoi volume
    of particles, number of vertices and face area of voronoi polyhedra
    and coordination number.
-   calculation of angular parameters such as [for identification of
    diamond
    structure](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.47.15717)
    and [Ackland-Jones](https://doi.org/10.1103/PhysRevB.73.054104)
    angular parameters.
-   [Centrosymmetry
    parameter](https://doi.org/10.1103/PhysRevB.58.11085) for
    identification of defects.
-   [Adaptive common neighbor
    analysis](https://iopscience.iop.org/article/10.1088/0965-0393/20/4/045021)
    for identification of crystal structures.

