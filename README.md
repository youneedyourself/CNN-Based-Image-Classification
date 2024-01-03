# CNN-Based-Image-Classifacation

 Building Image Classification model based on CNN model.

## Abstract

In this project, we build a CNN (Convolution Neural Nets) model for the image classification problem. You will use Pytorch to build the model, train the model on the training set and predict the labels of images in the test set.

This project is mainly referenced at: https://github.com/pbcquoc/cnn/blob/master/cnn.ipynb. Thanks a lot!

# Dataset
In this lesson, you must build a model to identify famous landmarks in Vietnam depicted in the photo. The training dataset includes 20k images, which is a small part of the dataset in the 2018 ZaloAI competition.

The picture below illustrates some famous places in Vietnam: One Pillar Pagoda, Ha Long Bay.

<div class="img-div" markdown="0">
    <img src="/assets/caodangsupham.png" />
</div>

<div class="img-div" markdown="0">
    <img src="/assets/chobenthanh.png" />
</div>

# Methods 
* Import data 
* Build the CNN model
* Model training
* Evaluate the model
* Use the trained model for prediction

## Results

Run the file `mainpy` to test your result trained model online in video (You can test your result in camera by change the line "v_cap = cv2.VideoCapture(0)" to "v_cap = cv2.VideoCapture()" in giaodiendiemdanh.py).

```
python main.py
```

The results achieved by the face detection and classification model trained on your dataset will vary depending on various factors such as the quality of your dataset, the size of the training set, and the chosen hyperparameters. It is recommended to experiment with different configurations to achieve the best results for your specific use case.

<p align="center">
  <img src="data/diemdanh.png"width="541" height="241">
</p>


## Contributing

Contributions to this repository are welcome. If you find any issues or would like to suggest improvements, please open an issue or submit a pull request.

## License
Feel free to use and modify the code for your own purposes.