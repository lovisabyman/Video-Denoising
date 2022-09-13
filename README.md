# Video Denoising
Video Denoising Project. This project was done as a part of the course EE 367: Computational Imaging by Lovisa Byman and Emil Vardar.

The project compares four different denoising methods for videos. The four methods are: Local Averaging Denoiser, Local Gaussian Denoiser, Non-local Means Denoiser in the spatial domain, and finally Non-local Means Denoiser in the spatial and temporal domain.

The code in 'main.py' reads in the videos, separates these videos into frames, and adds noise to each of these frames separately. The different denoising methods are then applied to each frame. Finally, the resulting denoised videos are put together (for qualitative comparison), and the mean-PSNR for the resulting video is calculated (for quantitative comparison).

To reconstruct the results given in this paper, run the code 'main.py' and the MATLAB code given in: 'M. Maggioni and A. Foi, V-BM4D software for video denoising, ver.1.0, Tampere University of Technology, 2014. [Online]. Available: https://webpages.tuni.fi/foi/GCF-BM3D' (To run this code follow the instructions on this page). Observe that the MATLAB code given on this page is not written by us.

Be sure that the videos are correctly named as stated in the file 'main.py' and that they are in the same directory as the code 'main.py'.
