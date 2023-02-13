# augmentation_imgaug
Provided is the code for performing 10 image augmentations on a training set, with forming corresponding labels (.txt), ready to be used in yolov5.

I have used the imgaug library to perform 10 data augmentations for the task of object detection. 
This code thus creates 10 images and 10 corresponding labels that are saved to 'images\train' and 'labels\train' folders respectively, that are required for YOLO.
One can use this code directly after using an annotating tool, keeping the paths of the folders as instructed in the notebook. 
Then, this folder can be zipped and uploaded to the YOLOv5 model directly, thus eliminating any manual work.
Also accompanied is some code for checking the bounding boxes on the augmented data, for example in rotation or translation.
