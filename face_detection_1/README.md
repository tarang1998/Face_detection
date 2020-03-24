#FACE_DETECTION


face detection using openCV and deeplearning

Uses a pre build caffe model

req:numpy,opencv-python,imutils

To run :

python detect_faces.py --image tarang.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

python detect_faces.py --image lena.jpg --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

python detect_faces_video.py --prototxt deploy.prototxt.txt --model res10_300x300_ssd_iter_140000.caffemodel

refer:https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/
