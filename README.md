edit modal in google colab

install dateset 

!pip install roboflow
from roboflow import Roboflow
rf = Roboflow(api_key="OqoibY20zY7jAAZBODDp")
project = rf.workspace("pp-xz7mq").project("test-trin")
version = project.version(1)
dataset = version.download("yolov8")

zip file
https://app.roboflow.com/ds/4hnIxFVgKz?key=Zo2Yy7kLwb
