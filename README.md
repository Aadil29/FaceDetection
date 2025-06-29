# FaceDetection

using this dataset from Kaggle (https://www.kaggle.com/datasets/fareselmenshawii/face-detection-dataset/data) to create a face detection model.

### Creating docker image

    docker build -t facedetection .

### Creating container

    docker run -it -p 8888:8888 `

-v "C:\Users\Aadil\Desktop\FaceDetection\app:/app" `  -v "C:\Users\Aadil\Desktop\FaceDetection\fd_dataset:/app/fd_dataset"`
facedetection

This is so changes on docker web file are also made on local version
