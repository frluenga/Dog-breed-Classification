# Final Project - Dog Breed Classifier Contents: 

### BLOG POST: https://medium.com/@frluenga/dog-breed-classification-deep-learning-c0378f7b9803

1. Project Definition 
2. Analysis - Model 
3. Conclusion 

# Requirements
opencv-python==3.2.0.6
h5py==2.6.0
matplotlib==2.0.0
numpy==1.12.0
scipy==0.18.1
tqdm==4.11.2
keras==2.0.2
scikit-learn==0.18.1
pillow==4.0.0
ipykernel==4.6.1
tensorflow==1.0.0
# Project Definition
 This project employs Convolutional Neural Networks (CNN) to construct a model capable of discerning a dog's breed from an uploaded image. In cases where the subject is not a dog, the model determines the breed resembling either a human or another animal. To accomplish this, 8,351 dog images spanning 133 breeds are utilized, alongside 13,233 human images for testing and differentiation. Convolutional Neural Networks, specialized in image classification and artificial vision, are employed. Additionally, Transfer Learning is implemented, adapting pre-trained networks to the current problem for efficient results. 
 # Analysis
 As outlined earlier, the project primarily focuses on images of dogs and humans. The dataset comprises 8,351 dog images, categorized into training, testing, and validation sets. Training set: 6,680 dog images, validation set: 835, and test set: 836. These images vary in size, quality, and breed distribution. The human images, totaling 13,233, depict different individuals in diverse positions and backgrounds. 
 # Model
 As stated in the problem description, a CNN, trained with Transfer Learning, is employed to simplify the identification of a dog's breed. This approach ensures the model can classify unseen images with a high probability among the 133 trained dog breeds. 
 # Conclusion
 The final model achieves a commendable 78.24% accuracy on the test dataset. Considering the original model's accuracy without Transfer Learning was only 3.94%, and a subsequent model with a single fully connected layer achieved approximately 48%, the final model's result is impressive. Tests on new images confirm accurate identification of dog breeds.

 # Resource:
* Data Source: [https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification].
* Acknowledgements: Udacity, Inc. "Nanodegree" is a registered trademark of Udacity. © 2011-2023 Udacity, Inc.


