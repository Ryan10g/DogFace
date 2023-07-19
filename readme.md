Dog Emotions Detector

My project is an attempt to have the ResNet-18 AI model to be able to recognize a dog's feelings. It is able to take a picture of a dog and return an emotion from angry, happy, relaxed and sad.
 
![add image descrition here](direct image link here)

## The Algorithm

Add an explanation of the algorithm and how it works. Make sure to include details about how the code works, what it depends on, and any other relevant info. Add images or other descriptions for your project here. 

This project uses the ResNet-18 AI model, which is a convolutional neural network that is trained on more than a million images in the ImageNet database. This model is an image detecting software, so it can also be re-trained with a separate database for a different output. I've re-trained this software to recognize the emotion of a dog after looking at an image. However, because emotion is complicated, and my data isn't that accurate, the results are also not as accurate. 

The code that causes machine learning uses neural networks to make the AI recognize images better. There are three categories of data I fed the AI. Training images, validation images and test images. The training images are used to show the AI and let it guess and train which image belongs in which category. This would help the AI find patterns in the images that it can then use to identify categories. Then there is the validation phase, where the AI gets tested to see what it's missing. It then goes through the same thing over and over again. The amount of times it repeats this process is called an epoch. For this project, I ran 50 epochs, which took around 10 hours. The more epochs are ran, the more accurate the model will be, since it has more training. Lastly, we can run the testing images through the model to see how well it performs, as the AI never saw those images. Also, if we are disappointed in the model's accuracy, we can keep training it. I didn't keep going because I don't have enough time to train it more times. 

In short, this project is a model that can recognize dog's emotions through a picture. It uses the ResNet-18 image recognition software and a Jetson-Nano. A lot of the instructions I found were from GitHub. 

## Running this project

1. First of all, you need a jetson-nano that has enough disk space to run some machine learning. Also, you will need reliable internet. If you are on windows, you can use the Nano using PuTTY. If you are on Mac, I have no idea how you will access the nano lmao.
2. On the nano, you need to download jetson-inference, including all it's image recognition software. You also want to have all the directories like python and training ready to go.
3. You also need to link the Nano to VSCode, where you can view photos. Also, the directories are easily readable from the contents bar on the left in VSCode.
4. Then, you want to go to Kaggle and download the dataset for dog emotions. The link is here: https://www.kaggle.com/datasets/devzohaib/dog-emotions-prediction. Download all the pictures and import it on to the nano, whether through a usb or through wget in the linux interface.
5. All the dog photos will come in 4 folders: angry, happy, relaxed, and sad. You should delete or add enough photos so that each emotion has the same amount of data to make the model a bit more accurate. 
6. Make sure to include any required libraries that need to be installed for your project to run
7. 

[View a video explanation here](video link)
