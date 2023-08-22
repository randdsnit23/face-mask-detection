# Face-Mask-Dectection
This program uses computer vision techniques and deep learning to detect whether individuals in a video stream are wearing masks or not. It loads a pre-trained face detection model and a pre-trained mask detection model. For every frame in the video stream, the program first detects the faces using the face detection model, and then predicts whether each detected face is wearing a mask or not using the mask detection model. The program then draws bounding boxes around the detected faces and adds labels indicating whether each person is wearing a mask or not, and their respective probabilities. Finally, the program displays the video stream with the mask detection results in real-time, and it will stop running when the user presses the 'q' key.

# How to run?
1. ```git clone https://github.com/li812/FaceMaskDectection.git```
2. ```cd DetectFaceMask```
3. ```pip install -r requirements.txt```
4. ```python detect_mask.py```

# How does it work?
All **pre-trained** deep neural network models used are in the ```models``` folder. <br>
The datasets used to train the modules can be found [here](https://drive.google.com/drive/folders/1XDte2DL2Mf_hw4NsmGst7QtYoU7sMBVG). <br>
Dataset details:
* 2165 images **with** a mask
* 1930 images **without** a mask

# What does this tool do?
1. Detects and highlights a face using your device camera
2. Detects if the face has a mask on or not
3. Displays feedback as shown below
