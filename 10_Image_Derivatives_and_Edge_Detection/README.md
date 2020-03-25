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

![simpleDerivatives_input.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/10_Image_Derivatives_and_Edge_Detection/simpleDerivatives_input.png)

* [histogramGraph.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramGraph.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb histogramGraph.cpp -o histogramGraph `pkg-config --cflags --libs opencv4`
./histogramGraph
```

![histogramGraph.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramGraph.png)


* [colorHistogramGraph.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/colorHistogramGraph.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb colorHistogramGraph.cpp -o colorHistogramGraph `pkg-config --cflags --libs opencv4`
./colorHistogramGraph
```

![histogramGraph.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/colorHistogramGraph.png)


* [multiDimHistogram.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/multiDimHistogram.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb multiDimHistogram.cpp -o multiDimHistogram `pkg-config --cflags --libs opencv4`
./multiDimHistogram
```

![multiDimHistogram.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/multiDimHistogram.png)
