# Dog-Breed-Classifier
Dataset - https://www.kaggle.com/c/dog-breed-identification

120 Dog Breeds are classified. 

Transfer Learning from InceptionV3 with ImageNet weights.

## Task:
Fine-grained image categorization is a challenging task that requires a deep understanding of the subtle differences between similar objects. In the case of canine breeds, this involves distinguishing between various breeds of dogs, such as Norfolk Terriers and Norwich Terriers, which have similar physical characteristics.

To practice fine-grained image categorization, a subset of ImageNet consisting of strictly canine images has been provided. This subset includes 120 breeds of dogs, and each breed has a limited number of training images available.

Due to the limited number of training images per class, the task of telling Norfolk Terriers from Norwich Terriers might prove to be more challenging than anticipated. The models will need to rely on learning subtle differences in physical features, such as the shape of the ears, the texture of the fur, and the size of the body.

The success of the models will depend on the quality and quantity of the training data, as well as the complexity of the model architecture. Deep learning techniques, such as convolutional neural networks (CNNs), have been shown to be effective in fine-grained image categorization tasks, but they require large amounts of training data and computational resources.

## Solution and Implementation:
InceptionV3 is a deep learning model architecture that has been used extensively for image classification tasks. It is a convolutional neural network (CNN) that is trained on a large dataset of images, and it has achieved state-of-the-art performance on various image classification tasks.

When it comes to classifying dog breeds, InceptionV3 can be used to identify the different physical features that distinguish one breed from another. By training the model on the provided subset of ImageNet consisting of strictly canine images, the model can learn to differentiate between the 120 different breeds of dogs, including Norfolk Terriers and Norwich Terriers.

To use InceptionV3 for this task, the first step is to pre-process the input images by resizing them to a fixed size and normalizing the pixel values. The next step is to fine-tune the pre-trained InceptionV3 model by retraining the final classification layer to classify the 120 different dog breeds.

To train the model, a set of training images and their corresponding labels must be provided. The model will then be trained on this data using a technique called backpropagation, which adjusts the model's parameters to minimize the error between its predicted output and the true label.

Once the model is trained, it can be used to classify new images of dogs based on their breed. The model will take the input image and output a probability distribution over the 120 different dog breeds, indicating the likelihood that the image belongs to each breed. The breed with the highest probability will be the predicted breed for the image.

## Conclusion:
In conclusion, the task of fine-grained image categorization of canine breeds is a challenging problem that requires careful consideration of the training data and model architecture. However, with the right techniques and resources, it is possible to accurately distinguish between similar breeds of dogs such as Norfolk Terriers and Norwich Terriers.

In summary, using InceptionV3 for classifying dog breeds is a powerful technique that can leverage the pre-trained knowledge of the model and adapt it to the specific task of classifying different dog breeds. With the right training data and tuning, the model can achieve high accuracy in distinguishing between similar breeds such as Norfolk Terriers and Norwich Terriers.
