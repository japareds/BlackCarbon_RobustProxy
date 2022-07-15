# Black Carbon Robust Proxy

Black carbon virtual sensor using ML proxy models

Low-cost sensors (LCS) developed by the SANS research group (http://sans.ac.upc.edu/).

The LCS monitor O3,NO2,NO,PMx,UFP at different threshold size.

The Black Carbon reference station monitoring is located at Palau Reial, Barcelona.


------------------------------------------------------------------------------------

ML models are used for estimating BC concentration indirectly by LCS measurements.
Given the data set size and characteristics 3 ML models are tested: SVR, RF, MLP.

The robust BC proxy models tests missing data imputatio during sensor deployment,
different monitoring frequencies and PCA noise filter.
