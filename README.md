# Image-Noise-Removal
Noise reduction is a critical step for enhancing image quality and extracting meaningful information from noisy images. One powerful approach to image denoising leverages the Fourier transform and frequency domain filtering.
The Fourier transform, a mathematical tool that decomposes an image into its constituent frequency components, provides a foundation for efficient image denoising.
Noise with periodic patterns or frequencies can be targeted and mitigated using Fourier-based filtering techniques that remove or suppress the specific frequency components responsible for the periodic noise.

Here, the process of image denoising is done using the Fast Fourier transform provided by the Numpy library in Python.

## Process of Noise Removal
![image](https://github.com/devika-kla/Image-Noise-Removal/assets/69448953/2d9c7283-e5ec-4eb4-b83e-b447c549c921)

#### 1. Image to Frequency Domain Conversion:

Take the 2D Fourier transform of the input image using the Fast Fourier Transform (FFT) algorithm. This converts the image from its spatial representation to its frequency representation.

![image](https://github.com/devika-kla/Image-Noise-Removal/assets/69448953/a5f75d34-6375-4bfb-ac73-bdffee788b4c)


#### 2. Frequency Domain Operations:

In the frequency domain, you can perform various operations such as filtering to remove the particular frequency components that causes the periodic noise.

![image](https://github.com/devika-kla/Image-Noise-Removal/assets/69448953/26813a35-0217-4aa4-9de6-b7456e0df5f6)


#### 3. Inverse Fourier Transform:

After processing the image in the frequency domain, you need to convert it back to the spatial domain using the inverse Fourier transform. This brings the image back to its original form but with the desired modifications.

![image](https://github.com/devika-kla/Image-Noise-Removal/assets/69448953/32f14b6a-6045-4389-a44a-d9946b05c465)
