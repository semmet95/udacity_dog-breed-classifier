# udacity_dog-breed-classifier
Udacity Deep Learning Nanodegree project

This is the second project in Udacity's Deep Learning Nanodegree program by Facebook.
In this notebook I've created a CNN model to classify images of dogs based on their breeds. And just for funsies, I've also programmed it to predict a dog breed for human faces as well, and return a cute little error message in case neither is detected.

I've used [this](https://github.com/ageitgey/face_recognition) repo to detect faces (it's really cool). And transfer learning with VGG16 and resnet152 pre-trained models to detect dogs in an image and to detect their breed respectively.

Put your images in the local_images folder to test the model on them in the last cell.


## To-Do
- the model is pretty bad at **not detecting** dogs in an image. So, for images that have neither faces nor dogs, the model still detects a dog 😅. Need to do something about that.
- The dog breed deecting accuracy is pretty good, 89%, but could still get better. I tried many ways, even unfroze all the pre-trained layers but still couldn't cross the 89% mark 😥. Need to work on that too.
