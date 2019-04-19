# PHDF-Dataset

PHDF-Dataset is a pedestrian head detection dataset based on fish-eye camera, including 2201 images labeled with 13,887 heads.

The dataset is now released by Shien-Ming Wu School of Intelligent Engineering in South China University of Technology, which can be downloaded through the following links:
- [Google Driver](https://drive.google.com/open?id=1rG4V8xqAkPhOIVnM69SAgOtCk2MSSp-C)
- [Baidu Web Drive](https://pan.baidu.com/s/1us3RUjKQNpvkoYYgZf_oNA) (Password: qzij)

Size = 251.6MB


## 1. Description

As far as we know, there is no pedestrian head detection dataset specifically for fish-eye camera. 
Therefore, we create a pedestrian head detection dataset PHDF based on fisheye camera with bird's eye view for our work.


## 2. Data Collection

We use the fish-eye camera to collect video data from three different scenarios. In addition, we download the video data shot in bird's-eye view with fish-eye camera from Bomni-DB dataset. 

2201 images are captured from video data of the four scenes, cropping the rest of the images and resizing each image to 512×512 pi. 
After that, we label all of the pedestrian heads in these images with rectangular boxes. 

The total number of labeled pedestrian heads is 13,887. 

Some of the labeled samples are shown below. Each picture is from four different scenarios, and all of the pedestrians that appeared in each image are labeled with green bounding boxes on their heads.
![Some samples from PHDF](https://github.com/SMWSIELab/PHDF-Dataset/blob/master/Pictures/Some%20samples%20from%20PHDF.png)


## 3. Database Constitution

We take 1800 images as the training set, and the remaining 401 images are used as the test set. 

There are two folders 'train' and 'test' in 'PHDF_dataset.zip'.
Pictures and XML files are in these two folders. Each XML file describes the location of pedestrian heads in the corresponding images, including pixel coordinates of the top left point and the bottom right point of head bounding boxes.  


## 4. Citation and Contact

Please consider to cite our paper when you use our database.

The citation will be released before long.

For any questions about this database please contact the authors by sending email to:

`liey2286@gmail.com`  `eeyhsong@gmail.com`

*Note: The PHDF database can be only used for non-commercial research purpose.*
