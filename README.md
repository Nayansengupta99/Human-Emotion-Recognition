# Human-Emotion-Recognition
Facial expression recognition has been an active research area over the past few decades, and it is still challenging due to the high intra-class variation. Traditional approaches for this problem rely on hand-crafted features such as SIFT, HOG and LBP, followed by a classifier trained on a database of images or videos. Most of these works perform reasonably well on datasets of images captured in a controlled condition, but fail to perform as good on more challenging datasets with more image variation and partial faces. In recent years, several works proposed an end-to-end framework for facial expression recognition, using deep learning models. Despite the better performance of these works, there still seems to be a great room for improvement. In this work, we propose a deep learning approach based on attentional convolutional network, which is able to focus on important parts of the face, and achieves significant improvement over previous models on multiple datasets, including FER-2013, CK+, FERG, and JAFFE. We also use a visualisation technique which is able to find important face regions for detecting different emotions, based on the classifier’s output. Through experimental results, we show that different emotions seems to be sensitive to different parts of the face. The system uses grayscale frontal face images of a person to classify six basic emotions namely happiness, sadness, disgust, fear, surprise and anger.

Points to be noted:
1. At first, you have to download the dataset from: https://drive.google.com/file/d/1hiv6SnVW3U0Brw9h72Iz1SW6GhxhbkEg/view
2. Load this dataset on to your project path.
3. In order to use Tensorflow in backend, you have to create a virtual environment. Go through this website to get an insight:https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
4. Then you have to switch to virtual env and have to install tensorflow.
5. After that compile the Classification_little_vgg.py
6. Here I have trained it by using Keras Optimizer: RMSprop. You can also use optimizers like SGD,Adam. And try to find out which is giving the best results.
7. Atlast run test.py and boom!, your model can read your emotions perfectly.

This approach of CNN using Keras with Tensorflow Backend is one of the most finest ways to detect emotions.


Output of the project
----------------------

![alt text](https://github.com/Nayansengupta99/Human-Emotion-Recognition/blob/master/Screenshot%202020-07-02%20at%206.47.56%20PM.png)


This model is capable to detect emotion of any face whether its an image from mobile, or a sticker or a cartoon.


