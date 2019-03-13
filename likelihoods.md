## March 13, 2019

# IceCube Follow-Up Maximum Likelihood Analysis

## Summary

$f$ = Probability of the CC SNe causing an IceCube neutrino being detected

$\lambda$ = Fraction of IceCube neutrinos from CC SNe

The log likelihood for CC SNe contributing to the IceCube neutrino flux is
![](./images/log_likelihood.png)
The log likelihood is maximized when the following condition is satisfied, which allows us to derive a proabbility of association for each candidate:
![](./images/probabilities.png)

**Problem:** Under some conditions, these probabilities summed to a number larger than 1. Need to figure out what conditions cause this behavior and how it affects our results.

### Without Redshift Information

![](./images/fov_z_pic_nospec.png)
![](./images/fov_z_df_nospec.png)
![](./images/lam_vs_ts_nospec.png)

### With Redshift Information

![](./images/fov_z_pic.png)
![](./images/fov_z_df.png)
![](./images/lam_vs_ts.png)

### Multiple (100) Realizations

![](./images/ts_distributions_190313.png)

## Conclusion
$\lambda f$ is only larger than 1 in the case where we have no redshift information and detect 2 or more candidates, which is unlikely but ocurrs when multiple realizations are analyzed. 

# KN Efficiency Plot

![](./images/kn2_easy_ri2_20.png)
![](./images/kn2_easy_ri4_1.png)
![](./images/kn2_easy_ri4_10.png)