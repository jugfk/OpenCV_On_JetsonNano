# 이미지 미분(Image Derivatives)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [simpleDerivatives.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/simpleDerivatives.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/10_Image_Derivatives_and_Edge_Detection

g++ -ggdb simpleDerivatives.cpp -o simpleDerivatives `pkg-config --cflags --libs opencv4`
./simpleDerivatives
```

![simpleDerivatives_total.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/simpleDerivatives_total.png)

* [SobelDerivatives.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/SobelDerivatives.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/10_Image_Derivatives_and_Edge_Detection

g++ -ggdb SobelDerivatives.cpp -o SobelDerivatives `pkg-config --cflags --libs opencv4`
./SobelDerivatives
```

![SobelDerivatives.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/SobelDerivatives.png)

* [ScharrDerivatives.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/ScharrDerivatives.cpp)
```
cd OpenCV_On_JetsonNano/10_Image_Derivatives_and_Edge_Detection

g++ -ggdb ScharrDerivatives.cpp -o ScharrDerivatives `pkg-config --cflags --libs opencv4`
./ScharrDerivatives
```

![ScharrDerivatives.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/ScharrDerivatives.png)

***
# 외곽선 검출(Edge Detection)
* [sobelEdgeDetector.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/sobelEdgeDetector.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/10_Image_Derivatives_and_Edge_Detection

g++ -ggdb sobelEdgeDetector.cpp -o sobelEdgeDetector `pkg-config --cflags --libs opencv4`
./sobelEdgeDetector
```
![sobelEdgeDetector.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/sobelEdgeDetector.png)
