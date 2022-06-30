# Download Datasets

https://www.cityscapes-dataset.com/

# Prepare Training Label

1. Download cityscapesScripts https://github.com/mcordts/cityscapesScripts
2. Modify 'cityscapesPath' in 'cityscapesScripts/cityscapesscripts/preparation/createTrainIdLabelImgs.py'
3. Run python createTrainIdLabelImgs.py

# Train
1. Modify 'path' in 'yolov5-sg\data\cityscapes.yaml'
2. Modify parse_opt in 'yolov5-sg\train.py'
3. Run python train.py