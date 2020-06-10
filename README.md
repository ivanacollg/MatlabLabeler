# matlab_image_labeler
Use of an object detector for automatic image labeling.

## Requirements

### Matlab 2019 or later
 - [Matlab 2020](https://es.mathworks.com/products/new_products/latest_features.html)

### Matlab Toolbox 
 - [Computer Vision](https://www.mathworks.com/products/computer-vision.html)

## Setup
```
  git clone [repositori_link]
```
- Place images to train detector in folder ```/train_data```
- Place validation images in folder ```/val_data```

## Manual labeling 
- Open ```Image Labeler``` app
- Add images from folder
- Create label
- Label images
- Save image labeling session as: ```labeling_session_[label_name]```
- Export image Labels as: ```labels_[label_name]```

## Training obj detector
The Object detector used in this repository is the ACF detector from matlab.
- Use file ```detector.mxl```
- To Do: Make file take label name as input

## Automatic labeling
- Open ```Image Labeler``` app
- Import images from ```/val_data```
- Import labels.
- Import detector method. 
- Run method on validation images. 
