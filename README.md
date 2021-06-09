# License Plate Detection (G-Parking Project)

We create a model to detec the license plate, crop it, and detec the character using Easyocr Library. We use VGG16 as based model, transfer learning from that model, and add some layer. Besides trying VGG16 as the base model, we also tried WPOD-NET as the base model. We changed various parameters added from both models, but the finished model is now the model with the best results we can get that fits our project. We choose a model that is not overfitting, because the other model is very overfitting, so we choose this model.Because there are only a few Indonesian license plate datasets, we also use foreign datasets so that the machine has more data to learn to recognize the license plate shape.

Base model : VGG16

Dataset    : https://www.kaggle.com/imamdigmi/indonesian-plate-number

             https://www.kaggle.com/andrewmvd/car-plate-detection
