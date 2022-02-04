## RipleyK

Python package to estimate Ripley's K statistic for a given number of 3D data points and assess if data are clustered/dispersed at a given scale r more than expected by chance, relative to N uniformly distributed data points.

- The input is a csv file with (x,y,z) coordinates of the data points, as well as a list of radii
- The output is a list of p-values, one for each radius, indicating significance of clustering

This approach has been applied in [Purshouse et al. (2022)](https://www.biorxiv.org/content/10.1101/2022.01.29.478046v1) to investige (non-)clustering of ecDNAs in patient-derived glioblastoma cell lines.