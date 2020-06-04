# BP-AIDE(Learning Blind Pixelwise Affine Image Denoiser with Single Noisy Images)

# Author: Jaeseok Byun and Taesup Moon
Code will be released.
Project page url: https://jaeseokbyun.github.io/BP-AIDE/

# Abstract

 Convolutional neural network (CNN)-based denoisers are recently shown to overwhelm the denoising performances 
 of the conventional prior- or optimization-based methods, particularly for the additive white Gaussian noise (AWGN) case. 
 However, those typical CNN-based denoisers had two main limitations: (1) the superb denoising performances for AWGN do not
 necessarily carry over to the signal-dependent real-noise cases and (2) the clean source images are required as targets for
 supervised training.  Both limitations are critical in practical real-noise denoising setting, since neither the noise 
 characteristics nor the clean source images are readily available for supervised training. While some recent work proposed
 CNN denoisers that are trained solely with noisy images, they still fall short of the classical baselines, \eg, BM3D,
 for blind real-noise denoising settings, in which nothing is known about the noise and only noisy images are available 
 for training. In this paper, we propose Blind Pixelwise Affine Image DEnoiser (BP-AIDE), which tackles above two limitations
 by combining variance stabilizing transformation (VST) technique with a recently developed unbiased estimate of the 
 mean-squared error (MSE) for a pixelwise affine denoiser. As a result, we show BP-AIDE can be blindly trained solely
 with single real-noise corrupted images and, to the best of our knowledge, first outperforms both CNN-based and 
 conventional denoisers for the same setting, on several real-world noisy image benchmark datasets. 


# Figure
< Visualization samples from BSD(68) which are corrputed by Gaussian noise (sigma=25) >
![스크린샷 2020-06-04 오후 9 02 57](https://user-images.githubusercontent.com/31755186/83754670-4c6a3700-a6a7-11ea-9b74-8da157981baf.png)
< Visualization samples from DND >
![스크린샷 2020-06-04 오후 9 08 39](https://user-images.githubusercontent.com/31755186/83754858-9bb06780-a6a7-11ea-8d3b-8cd97c00a83c.png)



# Table
<img width="1101" alt="Table1" src="https://user-images.githubusercontent.com/31755186/83738856-cabadf00-a68f-11ea-973b-bd22bf208f8f.png">
 <img width="1123" alt="Table2" src="https://user-images.githubusercontent.com/31755186/83738841-c5f62b00-a68f-11ea-8bcf-5fecdc86d625.png">

