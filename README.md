# The La Jolla Signed Difference Set Repository

This repository is an addition to the datasets on [The La Jolla
Combinatorics Repository](https://dmgordon.org), a website where I
maintain database of covering designs, difference sets, and circulant
weighing matrices.  Signed difference sets were described in [this
paper](https://arxiv.org) , and rather than adding it to the site, I'm
putting data from the paper here as a Jupyter notebook.  

This is an experiment in making a FAIR (Findable, Accessible,
Interoperable, Reusable) mathematical database (see [The FAIR Guiding
Principles for scientific data management and
stewardship](https://doi.org/10.1038/sdata.2016.18) for details.
After researching different approaches used by researchers in
many different scientific areas, implementing it as a Jupyter Notebook
seemed like the best current option.

This repository contains a json file with all the data from the paper,
and Sage code to read it and display the results.  It can be run
interactively with [binder](https://mybinder.org), or downloaded and
run locally.  Anyone wishing to further develop the code to do
research on signed difference sets is welcome to under the [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0)
license (giving attribution to the original work).

To run the notebook with binder, click here: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dmgordo/signed-difference-sets/master?filepath=signed_difference_sets.ipynb)

There were issues getting the SageMath kernel in binder. Hopefully
this will be ironed out in a future version, but for now the notebook
only runs python code.  For people who wish to do further development
there is Sage code at the bottom of sds_code.py to help get started.

## Contact 
If you encounter any problems with this repository, please report them
to <dmgordo@gmail.com>.
