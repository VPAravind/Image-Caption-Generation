# Image-Caption-Generation
Image Captioning using Tensorflow on Flickr 8K dataset

Dataset Used: Flickr 8K:

Dataset Obtained from: [FLICKR_8K](https://forms.illinois.edu/sec/1713398).


-----------------------------------------------------------------------------
This is implementation of a image caption generator from [Yumi's Blog](https://fairyonice.github.io/Develop_an_image_captioning_deep_learning_model_using_Flickr_8K_data.html). which generates a caption based on the things that are present in the image. Image captioning is a challenging task where computer vision and natural language processing both play a part to generate captions. This technology can be used in many new fields like helping visually impaired, medical image analysis, geospatial image analysis etc.

-----------------------------------------------------------------------------
## Dataset:

FLICKR_8K. This dataset includes around 1500 images along with 5 different captions written by different people for each image. The images are all contained together while caption text file has captions along with the image number appended to it. The zip file is approximately over 1 GB in size.


## Project sections:
* Cleaning the caption data
* Extracting features from images using VGG-16
* Merging the captions and images
* Building LSTM model for training
* Predicting on test data
* Evaluating the captions using BLEU scores as the metric


## Model
![](https://github.com/VPAravind/Image-Caption-Generator/blob/main/model_plot.png)
