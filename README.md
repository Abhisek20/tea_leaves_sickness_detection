# Tea Leave Sickness  Detection via GAN Augmentation
This project uses a new modified WGAN architecture to generate tea leaves images so as enhance the performances of image classification model. Predetermined image augmentation (e.g., rotation, flips, transpose, shear, etc.) techniques do mitigate the problem but they’re unable to capture the full data distribution hence limited utility. The performance of CNNs has been enhanced by the extensive usage of Generative Adversarial Networks (GAN) to produce enriched data. 

In our problem statement, we intend to solve tea leaves sickness detection where we propose using a new tea sickness dataset that has seven common tea diseases and thus can be used to train a deep learning model. We propose to feed the dataset images to a custom architecture based on wasserstein generative adversarial networks to generate synthetic images, then utilizing that along with real images train an image classification deep learning model which can predict the tea disease comparatively better than image classification model which is trained only on real and geometrically augmented images of the dataset.


Dataset link: https://data.mendeley.com/datasets/j32xdt2ff5

Generated images: 
![image](https://user-images.githubusercontent.com/69687280/204834574-8af3a280-476b-44d8-b0a1-b4199dbdbdcf.png)
