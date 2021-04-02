# Image-Classification-using-CNN
Image Classification, one of the techniques belonging to object recognition can be used in analysing objects appearing in an image. 

With the combination of results of three CNNs trained on custom images , the project presents an application of image classification to analyze the behaviour of a dog whether 
it is calm, angry, playful, curious or want to grab your attention and the activity it is doing, be it sleeping, running or sitting.

The MODEL1 is the first CNN trained on the classes of angry and sleeping images of dog.
The MODEL2 is the second CNN trained on the classes of running and sitting images of dog.
The MODEL3 is the third CNN trained on the classes of open and closed mouth images of dog.

The results after training the three models can show how a proposed architecture of CNN performs on different classes. 


The first step is to create a custom dataset and transform it to feed into the input layer. For the three CNNs, downloaded around 350 images from google belonging to each class
and then used generic data augmentation techniques to increase the training dataset three times. Later, converted all the images to grayscale and a fixed size of 100x100 which 
sharpened all of them.

![comparison](https://user-images.githubusercontent.com/52412432/113433477-e94b4d00-93fc-11eb-99e7-157e975dd371.png)

The following is the architecture of the CNN created, the information of the various layers and the activation function used:

![Conv Architecture](https://user-images.githubusercontent.com/52412432/113432616-5231c580-93fb-11eb-9130-a3e1c7864164.png)


We have trained three models which have given varying accuracy and this way we were able to observe and comment on how CNNs perform on different datasets. The following results
have been observed :

Later we combined the output of all models and predicted the behaviour and activity done by the dog in the input image. 
