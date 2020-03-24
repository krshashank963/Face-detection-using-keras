# Face-detection-using-keras
This keras model will detect the all face in the live cam and given pic

INSTALLATION
Currently it is only supported Python3.4 onwards. It can be installed through pip:

$ pip install mtcnn
This implementation requires OpenCV>=4.1 and Keras>=2.0.0 (any Tensorflow supported by
Keras will be supported by this MTCNN package). If this is the first time you use tensorflow, 
you will probably need to install it in your system:

$ pip install tensorflow
or with conda

$ conda install tensorflow
Note that tensorflow-gpu version can be used instead if a GPU device is available on the system, which will speedup the results.

USAGE
1.The bounding box is formatted as [x, y, width, height] under the key 'box'.
2.The confidence is the probability for a bounding box to be matching a face.
3.The keypoints are formatted into a JSON object with the keys 'left_eye', 'right_eye', 'nose', 'mouth_left', 'mouth_right'. Each keypoint is identified by a pixel position (x, y).
