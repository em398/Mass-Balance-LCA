# Mass-Balance-LCA
This repository contains the code used to calculate mass balances for a concrete production process in Brightway2 (Mutel, 2017). The methodology was developed by Ellie Marsh, Laura Hattam and Stephen Allen to support the journal paper **"[TITLE OF PAPER]" and citation. The work is part of the UNCARB project at the University of Bath (https://researchportal.bath.ac.uk/en/projects/towards-net-zero-carbon-buildings-tackling-uncertainty-when-predi).

The selected unit process is for concrete production, producing 2316 kg (or 1 m3) of concrete, where the mass inputs and their proportions have been based on Miller (2018). The LCA calculation was performed using Brightway2 (Mutel, 2017). 

The .CSV file contains the input database containing the process information. The LCA and Balance Calculation jupyter notebook contains the LCA calculation definition, uncertainty analysis and mass balance calculation. The results can be exported to Excel. The Figure jupyter notebook contains the results figures and associated code used in the paper. 

The excel file is a copy of the uncertainty characterisation excel spreadsheet provided on the Ecoinvent database website. The file can also be downloaded directly from here - https://19913970.fs1.hubspotusercontent-na1.net/hubfs/19913970/Knowledge%20Base/FAQ/excel-example_FAQ_uncertainty_ecoinvent.xlsx. 

References:

Miller, S.A., 2018. Supplementary cementitious materials to mitigate greenhouse gas emissions from concrete: can there be too much of a good thing? Journal of Cleaner Production [Online], 178, pp.587–598. Available from: https://doi.org/10.1016/J.JCLEPRO.2018.01.008.

Mutel, C., 2017. Brightway: An open source framework for Life Cycle Assessment. The Journal of Open Source Software [Online], 2(12), p.236. Available from: https://doi.org/10.21105/JOSS.00236.

Ecoinvent Centre. (2024). How to Interpret the Uncertainty Fields in ecoinvent? https://support.ecoinvent.org/about
