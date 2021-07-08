# Animal-Detection

This is a webapp project for detection of different dog breeds and cat breeds.
- utilize transfer learning of YOLOv4(Darknet) using a pre-trained coco dataset (weight)
- utilize Oxford Pets Dataset (roboflow), which contains 3680 labeled pictures of dogs and cats
- utilize tensorflow and flask


## requirements
* flask
* numpy
* tensorflow
* absl-py
* easydict
* matplotlib
* pillow

## how to use
export FLASK_APP=app <br />
export FLASK_ENV=development <br />
flask run <br />

