# Lung-and-Colon-Histopathological-Image-Classification
A Comparative Analysis of Deep Learning Models and Ensemble Methods for Lung and Colon Histopathological Image Classification

Dataset 
LC25000 LUNG AND COLON HISTOPATHOLOGICAL IMAGE DATASET

The dataset contains color 25,000 images with 5 classes of 5,000 images each. All images are 768 x 768 pixels in size and are in jpeg file format. Our dataset can be downloaded as a 1.85 GB zip file LC25000.zip. After unzipping, the main folder lung_colon_image_set contains two subfolders: colon_image_sets and lung_image_sets.

The subfolder colon_image_sets contains two secondary subfolders: colon_aca subfolder with 5000 images of colon adenocarcinomas and colon_n subfolder with 5000 images of benign colonic tissues.

The subfolder lung_image_sets contains three secondary subfolders: lung_aca subfolder with 5000 images of lung adenocarcinomas, lung_scc subfolder with 5000 images of lung squamous cell carcinomas, and lung_n subfolder with 5000 images of benign lung tissues.

This dataset can be downloaded from the link below:

https://academictorrents.com/details/7a638ed187a6180fd6e464b3666a6ea0499af4af

If you find this dataset useful and wish to cite it, you can use:

Borkowski AA, Bui MM, Thomas LB, Wilson CP, DeLand LA, Mastorides SM. Lung and Colon Cancer Histopathological Image Dataset (LC25000). arXiv:1912.12142v1 [eess.IV], 2019

https://arxiv.org/abs/1912.12142v1

Histopathological image of cancer cells analysis plays a critical role in the medical diagnostics, specifically for the detection and classification of cancers cells in the images. However, the complexity and variability inherent in medical images present the challenges for automated systems. The purpose of this project is to investigate how to use five cutting-edge customized deep learning models such as ResNet, Convolutional Neural Networks (CNN), EfficientNetB0, Vision Transformer (ViT) and VGG16 to improve the effectiveness and reliability of image classification on any given histopathology data set. 

The ensemble methods like majority voting, Dempster-Shafer theory and genetic algorithm-based optimization are utilized to take each model's strengths in the order to improve the classification performance and decrease error rates. After independently training and fine-tuning each model based on the dataset, the model's learned data were used for integrated ensemble methods.

By fusing the advantages of multiple models into a single framework this research also tackles the drawbacks of individual models, including the noise sensitivity and conventional issue of overfitting. After some color manipulation, an augmentation technique was used to assess the robustness of these five models. The dataset of colon and lung cancer images which is used in this research is divided into five classes "colon_aca", "colon_n", "lung_aca", "lung_n" and "lung_scc" for this in-depth analysis. The dataset, which originally included 25,000 photos with a resolution of 768 by 768, was reduced to a suitable size to improve efficiency and require less processing power.
A popular machine learning model architecture for classifying images, the convolutional neural networks (CNNs) may struggle to handle complicated datasets that call for sophisticated pattern recognition methods. Because of its scalability and effective management of the various parameters, EfficientNetB0, another model, was chosen in its place. The Vision Transformer model (ViT) was incorporated after CNN and EfficientNetB0, this model uses a self-attention mechanism to capture the long-range dependencies within the images. Then, ResNet was selected for its ability to train deep networks through residual learning, while VGG16 was included for its strength in extracting the hierarchical features across the layers, contributing noticeably to the performance of the model.

Ensemble techniques are also used to improve the performance. For example, Majority Voting offers a straightforward yet efficient means of combining forecasts. The Dempster-Shafer theory method, each model's output was given a degree of mass function to control uncertainty in the model predictions. Also, a Genetic Algorithm was used in last to optimize the model weights within the ensemble, enhance improved performance.
These ensemble methods outperform the accuracy of the individual models. The best classification accuracy was achieved by the Genetic Algorithm approach to maximize performance. This demonstrates how advanced ensemble techniques are and can improve histopathology images classification, which can make a broader diagnostic implication.
