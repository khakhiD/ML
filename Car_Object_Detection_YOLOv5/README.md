# YOLOv5 활용 차량 객체 인식
ML Programming 교과목 프로젝트에 제출하였습니다.

## Dataset
![datasetimg](https://storage.googleapis.com/kaggle-datasets-images/843852/1440019/f7e0ed99f527fdcdf7442d56f945ae93/dataset-cover.png?t=2020-08-24-19-59-18) 
### Car Object Detection
- YOLO Object Detection Playground | 1000+ Videos
- by EDWARD ZHANG
 

| testing_images        | training_images | sample_submission.csv | train_solution_bouunding_boxes(1).csv |
| --------------------- | --------------- | --------------------- | ------------------------------------- |
| 175 files             | 1001 files      | 2.87 kB               | 34.8 kB                               |

## Models
- YOLOv5
- YOLOv5s pretrained model
### train
- --img 67
- --batch 16
- --epochs 20
- --weights yolov5s.pt
- --name car-detection
