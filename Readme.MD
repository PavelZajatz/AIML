1. Install Python 3.7.6 and pip
(Skip this section if you already have Python 3.7.6)
Python Release Python 3.7.6
Release Date: Dec. 18, 2019 There are now newer bugfix releases
   of Python 3.7 that supersede 3.7.6 and Python 3.8 is…
www.python.org
2. Install ImageAI and dependencies
(Skip any of the installation instruction in this section
   if you already have the library installed )
- Tensorflow
pip install tensorflow==2.4.0
- Others
pip install keras==2.4.3 numpy==1.19.3 pillow==7.0.0 scipy==1.4.1 h5py==2.10.0 matplotlib==3.3.2 opencv-python keras-resnet==0.2.0
- Install the ImageAI library
pip install imageai --upgrade
3) Download the RetinaNet model file that will be used for object detection via this link. https://github.com/OlafenwaMoses/ImageAI/releases/download/essentials-v5/resnet50_coco_best_v2.1.0.h5/