# TGS-Salt-Identification-Challenge
TGS Salt Identification is a challenge on Kaggle.com.
Problem statement on Kaggle.com:

'Several areas of Earth with large accumulations of oil and gas also have huge deposits of salt below the surface. But unfortunately, knowing where large salt deposits are precisely is very difficult. Professional seismic imaging still requires expert human interpretation of salt bodies. This leads to very subjective, highly variable renderings. More alarmingly, it leads to potentially dangerous situations for oil and gas company drillers..

I tried U-Net architecure to segment area using a binary-corssentropy because we just have to segment if the salt is present or not (0 or 1).

I tried to replicate the U-Net without using much functions in the model so that anybody can understand the architecuture in just one glance and can change/modify it if required.

Many good techniques are being used in the model such as Transpose Convolution, adding skip connection by concatenation, EarlyStopping, reducing the learning using ReduceLROnPlateau etc.

The model achieved 0.0683 loss and  97% accuracy on training data and 1458 loss and 90% accuracy on validation data with 50 epochs.

Download the data from the link below.

Reference: 

Understanding Semantic Segmentation with UNET: https://towardsdatascience.com/understanding-semantic-segmentation-with-unet-6be4f42d4b47

Link to the Dataset on Kaggle.com: https://www.kaggle.com/c/tgs-salt-identification-challenge/

Tutorial on Subplots: https://www.youtube.com/watch?v=afITiFR6vfw&t=486s


Let me know if you need help in understanding U-Net.



Isaac,
https://www.linkedin.com/in/isaac-patole/
