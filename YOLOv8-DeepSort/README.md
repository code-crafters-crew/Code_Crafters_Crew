<H1 align="center">
Smart Traffic Control Using YOLOv8 Object Detection with DeepSORT Tracking </H1>

## Steps to run Code
- Clone repository
```
git clone https://github.com/code-crafters-crew/Code_Crafters_Crew.git
```
- Go to the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'
```
- Setting the Directory.
```
cd ultralytics/yolo/v8/detect
```
- Downloading the DeepSORT Files From The Google Drive 
```
https://drive.google.com/drive/u/3/folders/1u4sBAGx3NZZBVhYgFABBOQ1ZeONrxuUI
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder


- Run the code with mentioned command below.

- For yolov8 object detection + Tracking
```
 python predict.py model=yolov8l.pt source="demo1.mp4" show=True
