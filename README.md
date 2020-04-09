# BlankSkyfor3p5

#### An illustrative example based off of [Dessert et al. Science 2020](https://science.sciencemag.org/content/367/6485/1465) on searching for the $3.5$ keV line in XMM-Newton blank sky data.

This repository contains an example Jupyter notebook (`Jupyter/stacked_data_illustration.ipynb`) which allows the interested reader to analyze the stacked MOS data from [Dessert et al. Science 2020](https://science.sciencemag.org/content/367/6485/1465) for evidence of dark matter decaying into the $3.5$ keV line. 

Note that in this notebook we analyze the stacked MOS data from our fiducial dataset, which contains observations made between $5^\circ$ and $45^\circ$ away from the Galactic Center. In the original paper, we instead use a joint likelihood over these observations, which has various advantages explained in the text. Nevertheless this notebook provides an illustrative and interactive example for the reader.

In this notebook, we 
1. Calculate a $95\%$ limit on the active-sterile mixing angle $\sin^2(2\theta)$ due to overproduction of the data, and show that this limit of $\sin^2(2\theta) = 9.5 \times 10^{-11}$ already relevant relative to the $3.5$ keV line detections.
2. Perform a profile likelihood analysis in the region of $3.3$ to $3.8$ keV assuming a quadratic background and show we rule out the $3.5$ keV line with a $95\%$ limit of $\sin^2(2\theta) = 6.0 \times 10^{-12}$.
3. Perform a modified version of the analysis where we migitate possible systematics by subtracting from the fiducial data a "background" dataset constructed from observations made in the region between $60^\circ$ and $90^\circ$ away from the Galactic Center, and obtain a constraining $95\%$ limit of $\sin^2(2\theta) = 2.3 \times 10^{-11}$.
4. Perform a modified version of the analysis with additional background lines in the dataset at $3.3$ and $3.7$ keV, and again obtain a constraining $95\%$ limit of $\sin^2(2\theta) = 1.1 \times 10^{-11}$. 
5. Perform a modified version of the analysis in which we increase the width of our fitting range to $3.0$ to $4.0$ keV, and float background lines at $3.1$, $3.3$, $3.7$, and $3.9$ keV. Here we obtain a $95\%$ limit ruling out the $3.5$ keV line of $\sin^2(2\theta) = 8.0 \times 10^{-12}$.

Additional details, including plots and the full self-contained code, can be found in the notebook. The interested reader is free to experiment with aspects of the analysis to see how the results change. 

Please direct questions to bsafdi@umich.edu and cite the original paper if you use this data or these examples in a publication. The full data products are available at https://github.com/nickrodd/XMM-DM.