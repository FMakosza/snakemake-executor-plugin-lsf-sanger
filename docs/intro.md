[LSF](https://www.ibm.com/docs/en/spectrum-lsf/) is common high performance
computing batch system. This is a version of the [generic LSF executor plugin](https://github.com/BEFH/snakemake-executor-plugin-lsf) modified to better integrate with the Sanger compute environment and simplify pipeline execution.

Rule time and memory requirements are used to select an appropriate farm queue automatically, so users don't have to explicitly specify LSF queues for rules with resource declarations.
