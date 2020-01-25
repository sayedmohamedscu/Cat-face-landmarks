# Cat-face-landmarks

# Just for fun

### the main idea is to deal with dataset 
in this project I don't care about accuracy or model structure


kaggle dataset for cat face landmarks  https://www.kaggle.com/crawford/cat-dataset


![cat.jpg](https://github.com/sayedmohamedscu/Cat-face-landmarks/blob/master/cat.jpg)  

![data.png](https://github.com/sayedmohamedscu/Cat-face-landmarks/blob/master/data.png)  

Project contains:  
1. Cat facial landmarks detection with pretrained Mobilenetv2 and from scratch network
2. Soon cat face detector will be available

  

  
Used [Cat dataset on Kaggle](https://www.kaggle.com/crawford/cat-dataset) for training and validation.  
  
  
### Model Structure
1. Input (Full image 224x224) - **Facial landmarks model** - Output (9 landmarks points)
2. Input (Face image 224x224) - **Facial landmarks model** - Output (9 landmarks points)


# Requirement
- 
- Keras
- Numpy
- OpenCV
-soon will be avilable with pytorch




# Limitations
- Detect one cat per frame
- Cannot detect existence, this model thinks cat must be in the picture

# If you want to build an accurate one (pipeline) 
1-detect the cat existence
2-detect the face of the cat
3-apply landmarks detection


