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

Using pre-trained weights for MS COCO
```bash
It is included in {detector_demo.py} that downloading the pre-trained weights for MS COCO.
```

Run Demo
```bash
$ python detector_demo.py {YOUR_TEST_VIDEO}
```
<div align="center">
  <a href="https://www.youtube.com/watch?v=SJ_ri0njoHc"><img src="https://github.com/yonghankim/Mask-RCNN/blob/master/img/demo.JPG" alt="Mask RCNN COCO Object detection and segmentation
" width="550"></a>
</div>

