# Dog-Breed-Image-Classification-Using-CNNs-and-Transfer-Learning-In-Pytorch
This Project is all about building a Deep Learning Pipeline to process the real world , user supplied Images.Given an Image of a dog the algorithm will Identify an Estimate of the canine’s breed.If supplied an image of a human, the code will identify the resembling dog breed.

The CNN model which was built from scratch achieved a Test Accuracy of 16% with a Limited Dataset and also a Dataset that was imbalanced (This is even difficult for the Humans to correctly identify the Breed of the Dog). Applying Data Augmentation and Batch Normalization Could have helped the Model Performance a Little More.

The Model Achieved a Test Accuracy of 76% by Training with a Pre-Trained VGG16 Model, The Test Accuracy can be improved with the help of using other states of the art Pre-trained models such as ResNet and Inception Networks.

Along with exploring state-of-the-art CNN models for classification, This Project helped me to make important design decisions about the user experience for the app.

<h2>Datasets</h2>


[Dogs Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
Unzip the folder and place it in this project’s home directory, at
the location /dog_images.

[Humans Dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
Unzip the folder and place it in this project’s home directory, at
the location /lfw.
