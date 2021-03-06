[![Latest release](https://img.shields.io/github/release/fakenmc/micompm.svg)](https://github.com/fakenmc/micompm/releases)
[![Documentation](https://img.shields.io/badge/documentation-user_guide-brightgreen.svg)](docs/userguide.md)
[![MIT Licence](https://img.shields.io/badge/license-MIT-yellowgreen.svg)](https://opensource.org/licenses/MIT/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.931838.svg)](https://doi.org/10.5281/zenodo.931838)
[![JOSS](http://joss.theoj.org/papers/10.21105/joss.00430/status.svg)](https://doi.org/10.21105/joss.00430)

### Summary

_micompm_ is a [MATLAB]/[Octave] port of the original [micompr] [R] package for
comparing multivariate samples associated with different groups. It uses
principal component analysis to convert multivariate observations into a set of
linearly uncorrelated statistical measures, which are then compared using a
number of statistical methods. This technique is independent of the
distributional properties of samples and automatically selects features that
best explain their differences, avoiding manual selection of specific points or
summary statistics. The procedure is appropriate for comparing samples of time
series, images, spectrometric measures or similar multivariate observations. It
is aimed at researchers from all fields of science, although it requires some
knowledge on design of experiments, statistical testing and multidimensional
data analysis.

Follow _micompm_'s [User Guide] to get started.

### Dependencies

* [MATLAB Statistics toolbox] / [Octave statistics package]

### Documents

* [User Guide]
* [Contributing guidelines](CONTRIBUTING.md)
* [Code of conduct](CODE_OF_CONDUCT.md)

### References

#### Practice

* Fachada N, Rosa AC. (2018)
micompm: A MATLAB/Octave toolbox for multivariate independent comparison of
observations.
*Journal of Open Source Software*. 3(23):430.
https://doi.org/10.21105/joss.00430

#### Theory

* Fachada N, Lopes VV, Martins RC, Rosa AC. (2017)
Model-independent comparison of simulation output. *Simulation Modelling
Practice and Theory*. 72:131–149. http://dx.doi.org/10.1016/j.simpat.2016.12.013
([arXiv preprint](http://arxiv.org/abs/1509.09174))

### License

[MIT License](LICENSE)

[micompr]: https://github.com/fakenmc/micompr
[R]: https://www.r-project.org/
[MATLAB]: http://www.mathworks.com/products/matlab/
[Octave]: https://gnu.org/software/octave/
[User Guide]: docs/userguide.md
[MATLAB Statistics toolbox]: https://www.mathworks.com/products/statistics.html
[Octave statistics package]: https://octave.sourceforge.io/statistics/
