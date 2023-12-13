#YOLOv5 Deepsort Pedestrian Tracking Detection Count



-Implemented separate counting of inputs and outputs.

-Display detection categories.

-The default is to detect in the south/north direction. To detect different positions and directions, you can modify the points of two polygons in lines 13 and 21 of the main.py file.

-The default detection category can be added.

-The detection category can be modified in line 60 of the detector.py file.





##Operating environment



-Python 3.6+, pip 20+

-Pytorch

-Pip install - r requirements. txt




##How to run

1. 

    ```
    $ git clone https://github.com/dyh/unbox_yolov5_deepsort_counting.git
    ```
   
2. 

    ```
    $ cd unbox_yolov5_deepsort_counting
    ```

3.  
    ```
    $ python3 -m venv venv
    ```

4.  

    ```
    $ source venv/bin/activate
    ```
   
5.  

    ```
    $ python -m pip install --upgrade pip
    ```

6.  

    >  https://pytorch.org/get-started/locally/ 

    ```
    $ pip install torch==1.7.1+cu110 torchvision==0.8.2+cu110 torchaudio===0.7.2 -f https://download.pytorch.org/whl/torch_stable.html
    ```
   
7.  

    ```
    $ pip install -r requirements.txt
    ```

8.  
 
    ```
    capture = cv2.VideoCapture('./video/test.mp4')
    ```
   
9.  

    ```
    python main.py
    ```


## 

- https://github.com/Sharpiless/Yolov5-deepsort-inference
- https://github.com/ultralytics/yolov5/
- https://github.com/ZQPei/deep_sort_pytorch
