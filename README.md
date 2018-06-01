# Mask-RCNN
Implement Real-Time Semantic Segmentation with [Mask_RCNN](https://github.com/matterport/Mask_RCNN).


## Requirements
- Ubuntu 16.04
- Python 3.5
- Tensorflow 1.8
- Keras 2.1.6
- OpenCV 3.4


## Getting Started
Creating virtualenv
```bash
$ cd Mask-RCNN
$ virtualenv env --python=python3.5
$ source env/bin/activate
```

Install Dependencies
```bash
$ pip install -r requirements.txt
$ pip install git+https://github.com/philferriere/cocoapi.git#subdirectory=PythonAPI
```

Run Demo
```bash
$ python detector_demo.py {YOUR_TEST_VIDEO}
````



