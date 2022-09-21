
# The yolov7 object detection

This is a sample ncnn android project, it depends on ncnn library and opencv

https://github.com/Tencent/ncnn

https://github.com/nihui/opencv-mobile


## how to build and run
* Open this project with Android Studio, build it and enjoy!

## some notes
* Android ndk camera is used for best efficiency
* Crash may happen on very old devices for lacking HAL3 camera interface
* All models are manually modified to accept dynamic input shape
* Most small models run slower on GPU than on CPU, this is common
* FPS may be lower in dark environment because of longer camera exposure time

## screenshot
![Screenshot_2022_09_21_21_41_30_957_com_davidbejarcaceres_yolov7_framed](https://user-images.githubusercontent.com/17320214/191608125-228788e6-f813-4766-929b-99f7df87fffa.png)

## reference  

https://github.com/WongKinYiu/yolov7

https://github.com/nihui/ncnn-android-nanodet

https://github.com/Megvii-BaseDetection/YOLOX  

## If this helped you, don't forget to Star 🌟 the repo.
