# चेहरा-GAN

A simple weekend project, trained within a day or two using faicial features. 

**Demo:** [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Chehara-GAN/blob/master/%E0%A4%9A%E0%A5%87%E0%A4%B9%E0%A4%B0%E0%A4%BE_GAN.ipynb)

![visitors](https://visitor-badge.glitch.me/badge?page_id=vijishmadhavan.Chehara-GAN)


If you like what I'm doing you can:

- Follow me on [twitter](https://twitter.com/Vijish68859437)
- Check my other projects [GitHub](https://github.com/vijishmadhavan)
- You can sponsor me to support my open source work 💖 [sponsor](https://github.com/sponsors/vijishmadhavan?o=sd&sc=t)

**Changelog**

* 2022-08-023 [beta-v0.1](https://www.dropbox.com/s/d43p26ikzlxuyix/p4500.pkl?dl=1)


* 2022-08-022 Colab demo v0.1 [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Chehara-GAN/blob/master/%E0%A4%9A%E0%A5%87%E0%A4%B9%E0%A4%B0%E0%A4%BE_GAN.ipynb)


* 2022-08-022 Fast.ai model training [url](https://github.com/aarcosg/fastai-course-v3-notes/blob/master/refactored_by_topics/CNN_L7_gan_feature-loss.md)


### Image samples 


![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/ami-side.jpg)

![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/1_7-side.jpg)

![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/Adele_crop-side.png)

![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/90050137-4da1-44cc-b64b-0b9efc813148-side.jpg)


![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/0941881e-1b87-46d3-9b4e-10e9b8b4137b-side.jpg)


### Dataset

Dataset was generated using the below models. 

-[GPEN](https://github.com/yangxy/GPEN)

-[GFPGAN](https://github.com/TencentARC/GFPGAN)

-[FFHQ](https://github.com/NVlabs/ffhq-dataset) can be used, but generating a dataset would help in dealing with real image problems.

-Generated dataset was cropped to facial features and then trained.

![Superstar](https://github.com/vijishmadhavan/Chehara-GAN/blob/master/compare/facial%20feature-side.jpg)

### Weights

[beta-v0.1](https://www.dropbox.com/s/d43p26ikzlxuyix/p4500.pkl?dl=1)


### Implementation Details
- Model architecture: [fastai v1 u-net](https://fastai1.fast.ai/vision.models.unet.html)
- Paired image2image training: [fastai v1 superres notebook](https://github.com/aarcosg/fastai-course-v3-notes/blob/master/refactored_by_topics/CNN_L7_gan_feature-loss.md)

### Limitation

- I call this a beta v0.1 as it needs improvement, I would like to train this with a big dataset.



