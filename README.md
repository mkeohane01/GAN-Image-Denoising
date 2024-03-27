# GAN-Image-Denoising
Training Generative Adversarial Networks to de-noise smart phone images using the [SSID](https://abdokamel.github.io/sidd/) dataset


# Project Guidelines

Project 3-b Removing Unwanted Noises from Real Scene Images using GANs

- Ever clicked a picture with your mobile of the perfect sunset with just the right amount of reds and yellows? But when you looked at the picture, it was too grainy in texture, spoiling the quality of the capture. It could have been the next Instagram viral picture, but now you can’t show it to anyone. Well, nothing to worry about. GANs are here to your rescue.
- This grainy texture of the image is known as noise. While some minimal amount of noise is present in every clicked picture, sometimes very prominent due to external sources of interference, malfunctioning camera sensors, poor lighting conditions, etc. The process of removing noise from images is known as Image Denoising

- Denoising images become particularly important if the data collected is for training an ML/DL model, as poor quality images will lead to poor model performance.
- There are a lot of computer vision use cases where real-scene images are captured for example, semantic segmentation of scene, low light object detection, image analysis on CCTV camera feed, etc. It can also help restore the images that have degraded over time or were clicked with old low-quality cameras. GANs is one of the ways to resolve this problem. For training the model, you can use the very popular SIDD or Smartphone Image Denoising Dataset for training the model. It contains ~30,000 noisy images from 10 scenes under different lighting conditions using five different smartphones

- Please visualize the image before denoising and after denoising with GAN. Measure the image quality using PSNR, SSIM and FID etc