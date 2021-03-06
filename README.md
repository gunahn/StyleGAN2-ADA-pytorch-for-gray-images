# StyleGAN2-ADA-pytorch-for-gray-images

This repository contains the source code of the following paper:

 > Ahn, G., Choi, B.S., Ko, S., Jo, C., Han, H.S., Lee, M.C. and Ro, D.H., 2022. High‐Resolution Knee Plain Radiography Image Synthesis Using Style Generative Adversarial Network Adaptive Discriminator Augmentation. Journal of Orthopaedic Research®. doi:https://doi.org/10.1002/jor.25325
 
![figure_7](https://user-images.githubusercontent.com/58503653/126597885-68f98821-d633-4617-87bd-0e3aa2d938ec.png)
Real knee X-rays are shown in a and d. Images generated by DCGAN are shown in b and e. Images generated by StyleGAN2-ADA are shown in c and f.

Since the orgianl code (https://github.com/NVlabs/stylegan2-ada-pytorch) does not work in gray scale iamges, I modified the code for gray images (N_channel=1). 

you should check the [notebook file](https://github.com/gunahn/StyleGAN2-ADA-pytorch-for-gray-images/blob/main/StlyeGAN2-ADA-pytorch%20for%20gray%20images.ipynb) for the usuage of Stlyegan2-ada-pytorch for gray images. 

> 64-bit Python 3.7 and PyTorch 1.7.1. See https://pytorch.org/ for PyTorch install instructions.

> CUDA toolkit 11.0 or later. Use at least version 11.1 if running on RTX 3090. )

> Python libraries: pip install click requests tqdm pyspng ninja imageio-ffmpeg==0.4.3. We use the Anaconda3 2020.11 distribution which installs most of these by default.


Also, for comparison, I also uploaded DCGAN code [notebook](https://github.com/gunahn/StyleGAN2-ADA-pytorch-for-gray-images/blob/main/Knee%20X-ray%20images%20synthesis%20by%20DCGAN.ipynb) for 512X512X1 shape images 

