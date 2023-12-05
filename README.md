# Parking_Lot_Detection

#Install the package
  pip install ultralytics
#Model Training:
  Download dataset https://universe.roboflow.com/brad-dwyer/pklot-1tros/dataset/4
  # train model
  yolo task=detect mode=train model=yolov8m.pt data=datasets/data.yaml epochs=10 batch=32 imgsz=640



Use sagemaker-deployment.ipynb for sagemaker deploymnet(upload it in s3 model.tar.gz)
kafka.ipynb for producing the data
spark_sjob.ipynb for video analysis and store reults in mongodb
