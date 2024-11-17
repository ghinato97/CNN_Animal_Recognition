# Project Details:
## Dataset: 
CIFAR dataset is used. It consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

The classes are :

                        label_dict = {
                        
                        0:"airplane",
                        
                        1:"automobile",
                        
                        2:"bird",
                        
                        3:"cat",
                        
                        4:"deer",
                        
                        5:"dog",
                        
                        6:"frog",
                        
                        7:"horse",
                        
                        8:"ship",
                        
                        9:"truck"
                    }

    
## Model algorithm : 
Implementation of a convolutional neural network (CNN) for image analysis and classification.

Resnet MobileNetV2 pretrained (ImageNet weights) were used and last two classification layer were inserted.

## Image Pre-Processing
 Since CNN models were pre-trained with images of 224 x 224 pixel. 
 So the first step was a resize from
 
 32 x 32 -> 224 x 224
     
 Then we used the model preprocessing using the model.preprocess_input() function.
    
## Output: 
The models will classify the images based of the representations of vehicle  or animal.

## Evaluation of the Model:
Accuracy: Proportion of correctly classified images to the total.
Accuracy: Quality of positive predictions, indicating the proportion of correctly identified images.
## Analysis of Results:
Identification of any error patterns.
Evaluation of systematically confused image categories.
Examination of erroneous images and reflection on possible improvements to the model.
