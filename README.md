# asteroid-lightcurve_analysis
This Jupyter Notebook analyses the photometric data obtained by the GoChile telescope for the asteroid 22 Kalliope as part of the INSPIRO 2024 student projects at the University of Nova Gorica, Slovenia. 

Using the data, it performs Lomb-Scargle analysis to obtain the rotational period of the asteroid. Furthermore, it prepares the lightcurve data into the format expected by the codes for convex lightcurve inversion developed by M. Kaasalainen and J. Ďurech (see Kaasalainen & Torppa (2001) and Kaasalainen et al. (2001)). It reads the output file of these codes, translates it into an .obj file, and plots the 3D model of the asteroid 22 Kalliope.

Required Python packages: Astropy, Astroquery, Matplotlib, NumPy, Pandas, SciPy

The observational data are not included.
