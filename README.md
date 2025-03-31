# Denoising Chest X-Ray Images

# Abstract
Medical imaging is crucial for diagnosing and treating diseases, with chest X-rays being widely used. However, noise in these images degrades quality, hindering accurate diagnosis. Effective denoising techniques are necessary to enhance clarity while preserving diagnostic details. This project implemented and evaluated traditional filters and deep learning methods for denoising chest X-ray images. Traditional techniques included Mean, Median, Gaussian, Bilateral, Wiener, Wavelet, and Fourier filters. Deep learning approaches used are Generative Adversarial Networks (GANs), Autoencoders, and U-Net architectures. Performance was assessed using the Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM). The Autoencoder showed the best performance, providing higher noise reduction and structural preservation (PSNR = 29.441†, SSIM = 0.801) compared to other methods.

# Methodology
![methodology_flowchart](https://github.com/user-attachments/assets/19f44e75-e351-407d-9655-4901277c7ae0)
 Initially,five different types of noises were introduced into the existing dataset of chest X-ray images namely, Gaussian, Impulse, Salt and Pepper, Poisson and Speckle noise. Subsequently, various traditional filtering techniques and deep learning models were applied to restore the images and reduce noise. Finally, the performance of each method was evaluated and compared through comprehensive analysis, using metrics such as PSNR and SSIM to determine the most effective denoising approach.

# Results
## Traditional Filters
![trad_result](https://github.com/user-attachments/assets/394add98-a9f0-4ac9-8756-bc3cf0eff84e)
## GAN
![gan_results](https://github.com/user-attachments/assets/3462e9bc-ec11-459e-8657-0d85d419d6fa)
## U-Net
![unet_results](https://github.com/user-attachments/assets/47c1939c-4c62-449e-a9f8-c249f66c8e15)
## Autoencoder
![autoencoder_results](https://github.com/user-attachments/assets/9cc1289e-42e1-4086-8728-f4ce9759aacb)
## Performance Evaluation
![perf_evaluation](https://github.com/user-attachments/assets/555528b5-cb88-403a-8348-261930c3222a)


