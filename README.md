# mr-grip
Allele coding invariant version of MR-Egger/IVW.  This is work in progress.

The file `mr-grip.R` contains the `mr_grip` function which is compatible with the `TwoSampleMR` library.  The file `mr.R` is a hacked version of the same file in the `TwoSampleMR` library.  After source'ing this file, the `mr` function will run MR-GRIP automatically with the other default methods.

Alternatively, run MR-GRIP directly with
`mr_grip(b_exp, b_out, se_exp, se_out, parameters)`

Currently, no additional parameters are required.
