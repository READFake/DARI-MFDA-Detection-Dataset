# MASTER FACE DICTIONARY ATTACKS VIA REFLECTION-BASED IDENTIFICATION (DARI) DATASET:

## Introduction:
The **DARI** dataset contains 28,620 (29.40 GB) high-resolution facial images. Since MFDA detection is a binary classification problem, we collected 14,310 master face images using various start-of-the-art GAN models, including 6,580 images from StyleGAN, 6,580 images from StyleGAN2, and 1,150 images from StyleGAN3. In addition, we also collected 14,310 real facial images from different datasets, including 4,770 images from the FFHQ dataset, 4,770 images from the CelebA-HQ dataset, and 4,770 from the CelebA dataset.

The DARI dataset contains master face and real facial images in high resolutions with different environmental parameters, including illumination conditions, background colors, indoor or outdoor settings, face pose orientations, age, ethnicity, and appearances (e.g., wearing makeup and accessories). We also annotated the dataset with two different types of annotations:

1. **The Face Specular Highlight (FSH):** to identify highlight patterns from various reflective face regions. 

2. **The Image Annotation:** to identify the image label (either Real or Master Face).

Furthermore, all images were resized to  256  X 256. We also applied various types of augmentation techniques (e.g., horizontal flip, crop, and adjusting brightness and saturation) to increase the diversity of our training set.

## Dataset Download: 
We have released the **DARI** dataset, including  28,620 facial RGB images and the Image Annotations.

### Download links: 
[DARI-MFDA-DETECTION-DATASET-2023.zip (29.40 GB)](https://drive.google.com/drive/folders/1cglW3FO97PF2gd5oi6tPSxqXU9Yf-0pa?usp=sharing), to download full dataset.

## References: 

  [1]. Karras, Tero, Samuli Laine, and Timo Aila. "A style-based generator architecture for generative adversarial networks." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2019.
  
  [2]. Karras, Tero, et al. "Analyzing and improving the image quality of stylegan." Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2020.
  
  [3]. Karras, Tero, et al. "Alias-free generative adversarial networks." Advances in Neural Information Processing Systems 34 (2021): 852-863.
  
  [4]. Liu, Ziwei, et al. "Deep learning face attributes in the wild." Proceedings of the IEEE international conference on computer vision. 2015.
  
  [5]. Karras, Tero, et al. "Progressive growing of gans for improved quality, stability, and variation." arXiv preprint arXiv:1710.10196 (2017).

