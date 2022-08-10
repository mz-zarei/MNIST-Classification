# MNIST Classification Projects for CS 480/680 Fall 2019 (UWaterloo)

- Fine-tunning VGG11 model with MNIST
  - Training VGG11 model with MNIST
  - 
  <img src="model.png" width="600">
  
  - Inspecting the training process
    - Loss function vsepoch
    <img src="loss.png" width="600">
    - Accuracy vs epoch
     <img src="accuracy.png" width="600">
    
  - Inspecting the generalization properties
    - Test accuracy vs the degree of rotation
    <img src="rotation.png" width="600">
    - Test accuracy vs Gaussian noise
     <img src="noise.png" width="600">
  - Data augmentation using rotation and adding Gaussian noise
    - Test accuracy vs the degree of rotation after data augmentation
    <img src="rotation_aug.png" width="600">
    - Test accuracy vs Gaussian noise after data augmentation
    <img src="noise_aug.png" width="600">
    
- Bayes Gaussian Mixture Models (GMM)
  - Fitting Data set into K Gaussian Models
  - Inspecting impact of PCA
  <img src="pca.png" width="600">
  
