# Malaria-net

## Introduction

Malaria is a mosquito-borne infectious disease that affects humans and other animals. Malaria causes symptoms that typically include fever, tiredness, vomiting, and headaches. In severe cases, it can cause yellow skin, seizures, coma, or death. Symptoms usually begin ten to fifteen days after being bitten by an infected mosquito. If not properly treated, people may have recurrences of the disease months later. In those who have recently survived an infection, reinfection usually causes milder symptoms. This partial resistance disappears over months to years if the person has no continuing exposure to malaria.

![image](https://user-images.githubusercontent.com/33135767/97276018-ac32cb80-185c-11eb-8fa1-4eaf00b87d48.png)


### [Dataset Content]

The dataset contains 2 folders

* Infected
* Uninfected , with total of 27,558 images.

## Acknowledgements
This Dataset is taken from the official NIH Website: https://ceb.nlm.nih.gov/repositories/malaria-datasets/ And uploaded here, so anybody trying to start working with this dataset can get started immediately, as to download the dataset from NIH website is quite slow. 

Photo by Егор Камелев on Unsplash https://unsplash.com/@ekamelev

## Inspiration

Save humans by detecting and deploying Image Cells that contain Malaria or not!

## Uninfected images in BGR channel
![image](https://user-images.githubusercontent.com/33135767/97267511-480a0a80-1850-11eb-8ca0-69d715b29ec2.png) 

## Infected or  images in BGR channel
![image](https://user-images.githubusercontent.com/33135767/97267493-417b9300-1850-11eb-82b0-2ef6a58ddc68.png)

# Libraries used in this project:

* **Numpy** -- for matrix and array related operations
* **Matplotlib** -- for plotting
* **Opencv** -- for image processings opperation like blurring,thresholding etc etc.
* **Keras** -- for Deep learning architecture building

## My Sequential model for binary classification in Keras
<p align="center">
  <img src="https://user-images.githubusercontent.com/33135767/97267437-2f015980-1850-11eb-919f-3df63274d511.png"/>
</p>

## My Sequential model performance in training set

<p align="center">
  <img src="https://user-images.githubusercontent.com/33135767/97267552-58ba8080-1850-11eb-9aed-75746f2fb876.png"/>
</p>

## [GRADCAM] Algorithim

![image](https://user-images.githubusercontent.com/33135767/97299545-178b9600-187b-11eb-9135-175a05ec4718.png)

### For this classification model GRADCAM results

<p align="center">
  <img src="https://user-images.githubusercontent.com/33135767/97267430-2d379600-1850-11eb-803d-3e148bdcfb47.png"/>
</p>


## Tensorflow object detecton API result. Model used here is SSD

<p align="center">
  <img src="https://user-images.githubusercontent.com/33135767/97251271-8b9f4d00-182d-11eb-8780-b2315cd5f7d4.gif"/>
</p>


[Dataset Content]: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria
[GRADCAM]: https://arxiv.org/abs/1610.02391
