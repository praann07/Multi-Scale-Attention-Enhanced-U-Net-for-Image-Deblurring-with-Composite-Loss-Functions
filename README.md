Ultimately, the key contributions of this work are: 
• We propose a U-Net architecture augmented with selfattention, CBAM components, and multi-scale feature learning to boost feature refinement and capture global context.
• We propose a hybrid loss function combining pixelwise L1, perceptual (VGG16-based), and Fourier-domain losses to handle blur from both a spatial and a frequency viewpoint. This significantly improves the preservation of textures and high-frequency information.
• Our model has an average PSNR of around 28.1 dB and SSIM of approximately 0.815, which allows it to compete in deblurring performance using the GoPro dataset. The model shows a good trade-off between efficiency and performance with a fairly small model of roughly 30 million parameters, training efficiently with minimal augmentation and a simple training schedule.




You can find the trained model in this link
[https://drive.google.com/file/d/1arf95jOr3UNjUl79ya-PA4ImxcsY9pq_/view?usp=drive_link](https://drive.google.com/file/d/1arf95jOr3UNjUl79ya-PA4ImxcsY9pq_/view?usp=sharing)
