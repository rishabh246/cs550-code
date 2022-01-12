# cs550-code

This is the repository for our CS-550 project. 

The midterm and final reports can be found in `reports`.

To mirror the three contributions in our report, we have three submodules.
- `cs550-ct-verif` refers to our attempts to reproduce and extend the results of ct-verif (section 3).
- `klee-taint` refers to the symbolic execution + taint analysis tool we designed (section 4).
- `cs550-dudect` refers to the runtime verification approach to proving (empirically) constant-timeliness for binaries.

To reproduce our results:
- Clone this repository with `--recurse-submodules`
- Follow the detailed instructions given in each submodule to reproduce the results for that section.
