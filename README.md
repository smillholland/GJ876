Gliese 876 &mdash Supplementary Material
==================================================

This respository contains supplementary material to the paper <br />
Millholland, S., et al. <i> Gliese 876 &mdash Exemplar of Mean-Motion Resonance. </i> 2017, in prep

The file "posterior_samples.csv" contains the DE-MCMC posterior parameter samples for the four-planet coplanar fit 
described in Section 4 and summarized in Table 4 of the paper. To fit within GitHub's size limitations, the posterior
samples were thinned by uniqueness.

The columns of the file are as follows. For the planet
parameters, the columns are in orbital period order (i.e. planets "d", "c", "b", "e"). 

Columns
0-3 Periods (days)  <br />
4-7 Semi-major axes (AU)  <br />
8-11 Masses (Earth masses)  <br />
12-15 Eccentricities  <br />
16-19 Arguments of periastron (degrees)  <br />
20-23 Mean anomalies (degrees)  <br />
24-27 Arg. of peri. plus mean anom. (degrees)  <br />
28 Inclination (degrees)  <br />
29-34 RV zero-point offsets (m/s)  <br />
35-40 Jitter terms (m/s)  <br />
41 h (m/s)  <br />
42 w  <br />
45 logP_rot (log days) <br />
46 Lambda (days)  <br /> 
47 log-likelihood  <br />
