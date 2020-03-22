# 이미지 히스토그램(Image Histogram)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [histogramText.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramText.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb histogramText.cpp -o histogramText `pkg-config --cflags --libs opencv4`
./histogramText
```
![CreateThresholdLena.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/08_Image_Thresholding/CreateThresholdLena.png)

* [ThresholdingTypes.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/08_Image_Thresholding/ThresholdingTypes.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/06_Gaussian_function_and_filtering
g++ -ggdb ThresholdingTypes.cpp -o ThresholdingTypes `pkg-config --cflags --libs opencv4`
./ThresholdingTypes
```

![ThresholdingTypes.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/08_Image_Thresholding/ThresholdingTypes.png)
