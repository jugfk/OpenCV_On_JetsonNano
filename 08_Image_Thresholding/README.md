# 이미지 임계값(Image Threshholding)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [CreateThresholdLena.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/08_Image_Thresholding/CreateThresholdLena.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/08_Image_Thresholding

g++ -ggdb CreateThresholdLena.cpp -o CreateThresholdLena `pkg-config --cflags --libs opencv4`
./CreateThresholdLena
```
![filter2D.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/07_Filter2D_And_Vignetting/filter2D.png)

* [Vignette.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/07_Filter2D_And_Vignetting/Vignette.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/06_Gaussian_function_and_filtering
g++ -ggdb GaussianFiltering.cpp -o GaussianFiltering `pkg-config --cflags --libs opencv4`
./Vignette
```

![Vignette.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/07_Filter2D_And_Vignetting/Vignette.png)
