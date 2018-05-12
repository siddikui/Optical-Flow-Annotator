This repository contains an ipython notebook for the automatic annotations with bounding boxes for a single moving object in a video. 

## Environment

You can use the environment.yml file to setup your virtual environment.

| item        | detail                      |
| :---------  | :--------                   |
| OS          | Ubuntu 16.04 64 bit         |  
| Python      | Python 3.6                  |  
| Tensorflow  | Tensorflow 1.4              | 
| CUDA        | CUDA® Toolkit 8.0           |
| cuDNN       | cuDNN v5.1                  |
| OpenCV      | OpenCV 3.4.1                |


## Working

The code uses Optical FLow algorithm to track a moving object in a video from a relatively still camera and returns bounding boxes. The bounding boxes along with video frames are then stored in TFrecords format for training.

















