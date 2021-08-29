# Installing python libraries for face_recognition

## Dlib installation

### Windows
Requirements:
1. Visual Studio Express (possibly)
2. Python=3.8

Links:
1. [Dlib installation error? [duplicate]](https://stackoverflow.com/questions/51721695/dlib-installation-error)
2. [Install OpenCV 3 and Dlib on Windows ( Python only )](https://learnopencv.com/install-opencv-3-and-dlib-on-windows-python-only/)

### Mac with Apple M1
1. [Software Installation (Mac on Apple Metal M1)](https://github.com/jeffheaton/t81_558_deep_learning/blob/master/install/tensorflow-install-mac-metal-jul-2021.ipynb) <-- preferred mode (Thanks to [Jeff Heaton](https://sites.wustl.edu/jeffheaton/))
2. [Installing dlib on macos for python](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf)

Steps:
1. Follow the steps in the 1st link above to install `tensorflow`, `metal`, `keras`
2. Install dlib: `pip install dlib`
3. Install face_recognition: `pip install face_recognition`
4. Install opencv-python: `pip install opencv-python`
5. Install opencv-contrib-python: `pip install opencv-contrib-python`
6. Install tesseract: `brew install tesseract`
7. Install ffmpeg: `brew install ffmpeg`

### Ubuntu/Linux
1. install miniconda from [here](https://docs.conda.io/en/latest/miniconda.html#linux-installers)
2. create new environment: `conda create -n face_recognition python=3.8`
3. activate environment: `conda activate face_recognition`
4. install cmake: `sudo apt install cmake`
5. install build-essentials etc: `sudo apt install build-essential cmake pkg-config`
6. download and build dlib from [this link](http://dlib.net/) and following [this instructions](https://learnopencv.com/install-dlib-on-ubuntu/)
7. install cv2: `pip install opencv-python`
8. install face_recognition: `pip install face_recognition`
9. install tensorflow: `conda install tensorflow`
10. install keras: `conda install keras`



### Other notes:
## Opencv (cv2) installation
1. [opencv-python](https://pypi.org/project/opencv-python/)

## Face_recognition installation
1. [Windows Installation Tutorial #175](https://github.com/ageitgey/face_recognition/issues/175)
2. [Face Recognition](https://github.com/ageitgey/face_recognition)


