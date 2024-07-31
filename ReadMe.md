# Snakemake profiles for the geomicro lab servers and Great Lakes HPC at the University of Michigan

Each directory contains a config file with parameters for each server (e.g. available CPUs and memory). Profiles can be invoked using `snakemake [files or rules] --profile [path to profile directory]`

*Note: **Snakemake version 8** included major refactoring that among other things changed the underlying framework for handling job submission. It also requires major changes to the profile configuration file. Profiles for Snakemake version 8+ have been added and end in "8". They have been confirmed to work but have not been used as extensively as other profiles. Please open an issue for any profile related errors you encounter.*