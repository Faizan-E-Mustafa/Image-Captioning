# Keras implementation of Image-Captioning
Image captioning is a task that involves computer vision as well as Natural language processing. It takes an image and is able to describe whats going on in the image in plain English. 

* Keras With Tensorflow back-end  
* InceptionV3 for encoding
* LSTM for decoding 
* Hyper parameters used 

Hyper parameter| Value
-------------  | -------------
Embedding size |   300
Vocabulary size|   8256
Dropout        |   0.5
Batch Size     |   128
LSTM 1 Output  |   256
LSTM 1 Output  |   1000

I have also written a blog post describing my experience of implementing the project. You can find it [here.](https://medium.com/@faizanmustafa75/keras-implementation-of-image-captioning-model-3a7ab68e67d4)

If you want to use pretrained weights for LSTM model. You can download them [here.](https://drive.google.com/drive/folders/1FhKNcuaWLoRf1s99uzFL2EYjcLIVZH6Z)

Flickr8k dataset can be downloaded [here.](https://forms.illinois.edu/sec/1713398)

## Dependencies:
* Keras 2.1.6
* Tensorflow 1.7.0
* Numpy 
* Pandas
* Pickle 
* PIL
* Tqdm 

#### Note : It is recommended to use above mentioned version of Keras and Tensorflow.


## References
1)CS231n Winter 2016 Lesson 10 [Recurrent Neural Networks, Image Captioning and LSTM ](https://youtu.be/cO0a0QYmFm8?t=32m25s)

2)Another implementation of [image captioning model.](https://github.com/yashk2810/Image-Captioning)
