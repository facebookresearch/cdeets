The accompanying codes reproduce all figures and statistics presented in
"Calibration of P-values for calibration and for deviation of a subpopulation
from the full population," by Mark Tygert. This repository also provides LaTeX
and BibTeX sources for replicating the paper.

The main files in the repository are the following:

``tex/paper.pdf``
PDF version of the paper

``tex/paper.tex``
LaTeX source for the paper

``tex/paper.bib``
BibTeX source for the paper

``tex/jasa3.bst``
BibTeX style for the paper

``codes/dists.py``
Calculations of cumulative distribution functions for standard Brownian motions

``codes/subpop_weighted.py``
Functions for plotting deviation of a subpop. from the full pop. with weighting

``codes/acs.py``
Python script for processing the American Community Survey

``codes/psam_h06.csv.gz``
Microdata from the 2019 American Community Survey of the U.S. Census Bureau

Be sure to run ``gunzip codes/psam_h06.csv.gz`` to decompress the microdata.
Regenerating all the figures requires running in the subdirectory ``codes``
all Python files there, after having decompressed ``codes/psam_h06.csv.gz``.

The unit tests invoke [ImageMagick](https://imagemagick.org)'s ``convert``.

********************************************************************************

License

This cdeets software is licensed under the LICENSE file (the MIT license) in
the root directory of this source tree.
