# COV-MobNets
- A Mobile Networks Ensemble Model for Diagnosis of COVID-19 based on Chest X-ray images

# Abestract
Background:  The medical profession is facing an excessive workload, which has led to the development of various Computer-Aided Diagnosis (CAD) systems as well as Mobile-Aid Diagnosis (MAD) systems. These technologies enhance the speed and accuracy of diagnoses, particularly in areas with limited resources or remote regions during the pandemic. The primary purpose of this research is to predict and diagnose COVID-19 infection from chest X-ray images by developing a mobile-friendly deep learning framework, which has the potential for deployment in portable devices such as mobile or tablet, especially in situations where the workload of radiology specialists may be high. Moreover, this could improve the accuracy and transparency of population screening to assist radiologists during the pandemic.

Methods:  In this study, the Mobile Networks ensemble model called COV-MobNets is proposed to classify positive COVID-19 X-ray images from negative ones and can have an assistant role in diagnosing COVID-19. The proposed model is an ensemble model, combining two lightweight and mobile-friendly models: MobileViT based on transformer structure and MobileNetV3 based on Convolutional Neural Network. Hence, COV-MobNets can extract the features of chest X-ray images in two different methods to achieve better and more accurate results. In addition, data augmentation techniques were applied to the dataset to avoid overfitting during the training process. The COVIDx-CXR-3 benchmark dataset was used for training and evaluation.

Results:  The classification accuracy of the improved MobileViT and MobileNetV3 models on the test set has reached 92.5% and 97%, respectively, while the accuracy of the proposed model (COV-MobNets) has reached 97.75%. The sensitivity and specificity of the proposed model have also reached 98.5% and 97%, respectively. Experimental comparison proves the result is more accurate and balanced than other methods. 

Conclusion:  The proposed method can distinguish between positive and negative COVID-19 cases more accurately and quickly. The proposed method proves that utilizing two automatic feature extractors with different structures as an overall framework of COVID-19 diagnosis can lead to improved performance, enhanced accuracy, and better generalization to new or unseen data. As a result, the proposed framework in this study can be used as an effective method for computer-aided diagnosis and mobile-aided diagnosis of COVID-19. The code is available publicly for open access at https://github.com/MAmirEshraghi/COV-MobNets.

# Figures:
  
![3-ensemble](https://user-images.githubusercontent.com/92205834/226120620-e8bee5d9-e9a7-4300-92ae-1ad1d4f11f82.png)
Fig. 1: Overall framework of COV-MobNets (proposed model)

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/be5e675b-36fe-4849-9c4e-2f83a705cd6e)
- Fig. 2: The overall overview of the improved MobileNetV3 architecture, comprising (a) MobileNetV3 block; (b) Depthwise separable convolution block; (c) Squeeze-and-excitation block; (d) Classification block

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/58fba965-e4f4-4a38-8627-d50d72683ccb)
- Fig. 3: Overall overview of proposed MobileViT architecture consists of (a) MobileViT block; (b) Transformer Encoder block; (c) Classification block

# Results:

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/c73b81c3-465e-415c-b742-7fa25ae81845)
Fig. 4: Loss and accuracy change curves of training and validation sets for the MobileViT model

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/8d0c8800-3d93-4dfe-8f2c-15821f2a7765)
Fig. 5: Loss and accuracy change curves of training and validation sets for the MobileNetV3 model.

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/7fcde99c-ce11-4a2a-b842-5319e2b416aa)
Fig. 6: MobileViT model confusion matrix

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/b26c06a8-7817-4fce-a786-413c15cdd4e1)
Fig. 7: MobileNetV3 model confusion matrix

![image](https://github.com/MAmirEshraghi/COV-MobNets/assets/92205834/d54aa455-05d0-484d-a542-b3646559db2c)
Fig. 8: COV-MobNets model confusion matrix

# Cite:

"M. A. Eshraghi, A. Ayatollahi, and S. B. Shokouhi, “COV-MobNets: a mobile networks ensemble model for diagnosis of COVID-19 based on chest X-ray images,” BMC Med. Imaging, vol. 23, no. 1, p. 83, 2023, doi: 10.1186/s12880-023-01039-w."
