# DR_ATE_estimation

This is a test repository with code which implements doubly robust average treatment effect estimation using data from the Job Training Partnership Act (JTPA) Study. Details of this study may be found in [[1]](#1). Details and motivations for doubly robust estimation may be found in multiple papers with [[2]](#2) being the most relevant for this discussion (see also [this](https://www.youtube.com/watch?v=eHOjmyoPCFU&ab_channel=BeckerFriedmanInstituteatUChicago-BFI) useful presentation by Victor Chernozhukov). 

The complete dataset may be downloaded from https://www.upjohn.org/data-tools/employment-research-data-center/national-jtpa-study, but only a small selection is used for this exercise (included as `jtpa_reasons_outcome.csv`).

## References
<a id ="1">[1]</a>
H. Bloom, L. Orr, S. Bell, G. Cave, and Doolittle. The National JTPA Study: Title II-A Impacts
on Earnings and Employment at 18 Months. Bethesda, Md.: Abt Associates Inc, 1993.

<a id ="2">[2]</a>
Victor Chernozukhov, Denis Chetverikov, Mert Demirer,
Esther Duflo, Christian Hansen, Whitney Newey and James Robins.
Double/debiased Machine Learning for Treatment and Structural Parameters. The Econometrics Journal, 2018.
