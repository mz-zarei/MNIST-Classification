# MNIST Classification Projects for CS 480/680 Fall 2019 (UWaterloo)

- Fine-tunning VGG11 model with MNIST
  - Training VGG11 model with MNIST
  ![model](model.png)
  
  - Inspecting the training process
    - Loss function vsepoch
    ![Loss function](loss.png | width=400)
    - Accuracy vs epoch
    ![Accuracy](accuracy.png | width=400)
    
  - Inspecting the generalization properties
    - Test accuracy vs the degree of rotation
    ![acc vs rotation](rotation.png | width=400)
    - Test accuracy vs Gaussian noise
    ![acc vs noise](noise.png | width=400)
  - Data augmentation using rotation and adding Gaussian noise
    - Test accuracy vs the degree of rotation after data augmentation
    ![acc vs rotation](rotation_aug.png | width=400)
    - Test accuracy vs Gaussian noise after data augmentation
    ![acc vs noise](noise_aug.png | width=400)
    
- Bayes Gaussian Mixture Models (GMM)
  - Fitting Data set into K Gaussian Models
  - Inspecting impact of PCA
  ![result](pca.png | width=400)
  
