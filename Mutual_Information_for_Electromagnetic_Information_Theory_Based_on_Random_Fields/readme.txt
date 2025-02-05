﻿This simulation code package is mainly used to reproduce the results of the following paper [1]:

[1] Z. Wan, J. Zhu, Z. Zhang, L. Dai, and C. B. Chae, "Mutual Information for Electromagnetic Information Theory Based on Random Fields," IEEE Trans. Commun., vol. 71, no. 4, pp. 1982-1996, Apr. 2023. 

*********************************************************************************************************************************
If you use this simulation code package in any way, please cite the original paper [1] above. 
 
The author in charge of this simulation code pacakge is: Zhongzhichao Wan (email: wzzc20@mails.tsinghua.edu.cn).

Reference: We highly respect reproducible research, so we try to provide the simulation codes for our published papers (more information can be found at: 
http://oa.ee.tsinghua.edu.cn/dailinglong/publications/publications.html). 

Please note that the MATLAB R2021b and Wolframe Mathematica 11.1 is used for this simulation code package, and there may be some imcompatibility problems among different MATLAB and Mathematica versions. 

Copyright reserved by the Broadband Communications and Signal Processing Laboratory (led by Dr. Linglong Dai), Beijing National Research Center for Information Science and Technology (BNRist), Department of Electronic Engineering, Tsinghua University, Beijing 100084, China. 
*********************************************************************************************************************************
Abstract of the paper: 

Traditional channel capacity based on the discrete spatial dimensions mismatches the continuous electromagnetic fields. For the wireless communication system in a limited region, the spatial discretization may results in information loss because the continuous field can not be perfectly recovered from the sampling points. Therefore, electromagnetic information theory based on spatially continuous electromagnetic fields becomes necessary to reveal the fundamental theoretical capacity bound of communication systems. In this paper, we propose analyzing schemes for the performance limit between continuous transceivers. Specifically, we model the communication process between two continuous regions by random fields. Then, for the white noise model, we use Mercer expansion to derive the mutual information between the source and the destination. For the close-form expression, an analytic method is introduced based on autocorrelation functions with rational spectrum. Moreover, the Fredholm determinant is used for the general autocorrelation functions to provide the numerical calculation scheme. Further works extend the white noise model to colored noise and discuss the mutual information under it. Finally, we build an ideal model with infinite-length source and destination which shows a strong correspondence with the time-domain model in classical information theory. The mutual information and the capacity are derived through the spatial spectral density.

*********************************************************************************************************************************
How to use this simulation code package?

Fig. 3 can be generated by directly running the "non-white simulation/data_plot.m" file. The data is generated by the "non-white simulation/data_generate_non_white.nb" file. 
Fig. 4 can be generated by directly running the "Fourier transform of the Green function/Fourier_of_Green_function.m" file. The data is generated by the "Fourier transform of the Green function/data_generate_Fourier_of_Green_function.nb" file.
Fig. 5 can be generated by directly running the "waterfilling/waterfilling.m" file. The data is generated by the "waterfilling/Water_filling_data_generate" file.  

*********************************************************************************************************************************
Enjoy the reproducible research!
