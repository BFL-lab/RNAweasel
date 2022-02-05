
# RNAweasel and support utilities

This repository contains the programs `RNAweasel` and `RNAweasel_cl`
along with a few other required programs invoked by them: `mf2annot`
and `distpin`.

These programs were developed in the early 2000s at the BFL lab.

## Installation warning

For the moment this distribution contains the code as
exactracted from a custom installation at the BFL lab. As
such it still contains a bunch of hardcoded filesystem paths
specific to the original machines. Some cleanup and adjustements
are still necessary and forthcoming (Feb, 2022).

## History

The original sources were maintained in a CVS repository and the
exact history of the files have not been preserved. However,
the subdirectory `cvs_history` contains a full set of the outputs
of the `cvs log` and `cvs annotate` commands for each source file.
This provides some information about the authors of these programs.

## External Requirements

The `distpin` program depends on a few external executables not
provided here:

* gblocks
* ali2puz
* puzzle
* dnadist

## Contact

For help with this distribution, create a GitHub ticket or
contact `pierre.rioux@mcgill.ca`

