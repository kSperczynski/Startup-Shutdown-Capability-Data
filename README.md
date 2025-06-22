# Startup-Shutdown-Capability-Data

This repository holds the input and output data used for the paper "Start-Up and Shut-Down Capabilities in Unit Commitment Model with Fully Flexible Temporal Resolution".
The repository is organized as follows:

The top-level directory `input` contains the files that were used to run experiments on the Tulipa Energy Model. The directory is further subdivided into `non-investable` and `investable` sub-directories. The former contains the data used for experiments in the main body of the paper, while the latter contains the data used for experiments in the Appendix. The files are compatible with Tulipa v0.15.1.

The top-level directory `output` contains the files that were used for the results in the paper. The directory is further subdivided into `non-investable` and `investable` sub-directories. The former contains the data obtained from experiments in the main body of the paper, while the latter contains the data obtained from experiments described in the Appendix. These include the solutions for variables from the model, prefixed with `var_`, as well as the cost for the system and the computed cost for specific regions, stored in `objective_value.txt`.

The run and creation times reported in the results are prefixed with `NE_`; this is simply legacy naming, but it corresponds to equivalent result names when the prefix (and optional suffix in the cases with trade) are ommitted.