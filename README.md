# FaceDetection

using this dataset from Kaggle (https://www.kaggle.com/datasets/fareselmenshawii/face-detection-dataset/data) to create a face detection model.

### Creating docker image

    docker build -t facedetection .

### Creating container

    docker run -p 8888:8888 --name my-jupyter-container facedetection
