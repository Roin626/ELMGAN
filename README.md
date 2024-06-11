# ELMGAN

# abstract
Cell segmentation and counting is a time-consuming and important experimental step in traditional biomedical research. Many current counting methods are Point-based methods which require exact cell locations. However, there are few such cell datasets with detailed object coordinates. Most existing cell datasets only have the total number of cells and a global segmentation annotation. To effectively use existing datasets, we divide the cell counting task into the cell’s number prediction and cell segmentation. We propose a GAN-based efficient lightweight multi-scale-feature-fusion multi-task model (ELMGAN). To coordinate the learning of these two tasks, we propose a Norm-Combined Hybrid loss function (NH loss) and use the method of the generative adversarial network to train our networks. We propose a new Fold Beyond-nearest Upsampling method (FBU) in our lightweight and fast multi-scale-feature-fusion multi-task generator (LFMMG), which is twice as fast as the traditional interpolation upsampling method. We use multi-scale feature fusion technology to improve the quality of segmentation images. LFMMG reduces the number of parameters by nearly 50% compared with U-Net and gets better performance on cell segmentation. Compared with the traditional GAN model, our method improves the speed of image processing by nearly ten times. In addition, we also propose a Coordinated Multitasking Training Discriminator (CMTD) to refine the accuracy of the details of the features. Our method achieves non-Point-based counting that no longer needs to annotate the exact position of each cell in the image during the training and achieves excellent results in cell counting and segmentation.


# structure of ELMGAN
![image](https://github.com/Roin626/ELMGAN/assets/44090641/cdc3221c-78b2-438c-b3d2-4a0309005d6e)




# Citation

If you find this code useful for your research, please consider citing:
```bibtex
@article{DENG2022109434,
title = {ELMGAN: A GAN-based efficient lightweight multi-scale-feature-fusion multi-task model},
journal = {Knowledge-Based Systems},
volume = {252},
pages = {109434},
year = {2022},
issn = {0950-7051},
doi = {https://doi.org/10.1016/j.knosys.2022.109434},
url = {https://www.sciencedirect.com/science/article/pii/S0950705122007250},
author = {Lijia Deng and Shui-Hua Wang and Yu-Dong Zhang},
keywords = {Convolutional neural network, Generative adversarial networks, Cell segmentation, Cell counting},
abstract = {Cell segmentation and counting is a time-consuming and important experimental step in traditional biomedical research. Many current counting methods are Point-based methods which require exact cell locations. However, there are few such cell datasets with detailed object coordinates. Most existing cell datasets only have the total number of cells and a global segmentation annotation. To effectively use existing datasets, we divide the cell counting task into the cell’s number prediction and cell segmentation. We propose a GAN-based efficient lightweight multi-scale-feature-fusion multi-task model (ELMGAN). To coordinate the learning of these two tasks, we propose a Norm-Combined Hybrid loss function (NH loss) and use the method of the generative adversarial network to train our networks. We propose a new Fold Beyond-nearest Upsampling method (FBU) in our lightweight and fast multi-scale-feature-fusion multi-task generator (LFMMG), which is twice as fast as the traditional interpolation upsampling method. We use multi-scale feature fusion technology to improve the quality of segmentation images. LFMMG reduces the number of parameters by nearly 50% compared with U-Net and gets better performance on cell segmentation. Compared with the traditional GAN model, our method improves the speed of image processing by nearly ten times. In addition, we also propose a Coordinated Multitasking Training Discriminator (CMTD) to refine the accuracy of the details of the features. Our method achieves non-Point-based counting that no longer needs to annotate the exact position of each cell in the image during the training and achieves excellent results in cell counting and segmentation.}
}
```
