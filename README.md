# cs550-code

This is the repository for our CS-550 project. 

The midterm and final reports can be found in `reports`.

To mirror the three contributions in our report, we have three submodules.
- `cs550-ct-verif` refers to our attempts to reproduce and extend the results of ct-verif (Section 3).
- `klee-taint` refers to the symbolic execution + taint analysis tool we designed (Section 4).
- `cs550-dudect` refers to the runtime verification approach to proving (empirically) constant-timeliness for binaries (Section 5).

To reproduce our results:
- Clone this repository with `--recurse-submodules`
- Follow the detailed instructions given in each submodule to reproduce the results for that section.
