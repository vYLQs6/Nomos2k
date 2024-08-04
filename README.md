# Nomos2k
Nomos2k dataset

---

This dataset is originally compiled and packaged by Musl.

https://github.com/muslll

neosr project:

https://github.com/muslll/neosr

---

```
Dataset Name: Nomos2k
License: check sources
Purpose: Realistic SR
KernelGAN Scale: 4x
Description: A dataset containing 2536 images of 2000px. I hand selected it from multiple sources, based on the following criteria:
- High signal-to-noise ratio (low noise)
- Diverse. 
- Sharp (no motion blur, shallow DOF is ok)
- Contains mixed and complex textures/shapes that cover most part of the image

Raw images were processed on rawtherapee using prebayer deconvolution, AMaZe and AP1 color space.

KernelGAN was trained using DLIP on all images, with scale 4x and up to 5k iter, instead of 3k. Hopefully it increases the accuracy of kernels. All files are provided on "kernelgan" folder. Note: in order to use it on traiNNer, you have to give dataroot_kernels path, along with enabling "realistic" under the resizing presets. 

I encourage everyone to give it a try and, if possible, mirror the dataset. For now it was made available on MEGA, but I plan to mirror it on other solutions.
```
