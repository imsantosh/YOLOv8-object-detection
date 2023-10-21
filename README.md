# YOLOv8-object-detection
Object Detection, segmentation &amp; classification using YOLO v8

# Visit below github link for documentation
https://github.com/ultralytics/ultralytics

# Steps are below
1) To train model on custom data set first annotate the test, train and validation model and generate ymal file
2) Upload the data into Google drive as we will train the model over there into google colab using GPU
3) Post traning best & last model will be saved into google drive
4) Use best model for predection

# To Annotate the image use install labelImg(refer the install guideline into below url)
https://github.com/HumanSignal/labelImg

# Update the Yaml file with actual images(train, val, number of class & class list) file path of your google drive, Yolov8 was the folder where I have uplaoded the data
1) train: /content/drive/MyDrive/Yolov8/data/train/images
2) val: /content/drive/MyDrive/Yolov8/data/valid/images
3) nc: 5
4) names: ['Helmet', 'Goggles', 'Jacket', 'Gloves', 'Footwear']



