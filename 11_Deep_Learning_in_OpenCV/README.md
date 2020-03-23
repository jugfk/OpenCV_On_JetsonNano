# OpenCV에서 딥러닝 라이브러리 쓰기(Image Histogram)
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
python3 download_gdrive.py 1uP9N5E2Jjm6-RrVwHLdBc00qQZeYH7Uj /home/ubuntu/OpenCV_On_JetsonNano/11_Deep_Learning_in_OpenCV ./models/frozen_inference_graph.pb
```

* [histogramText.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramText.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb histogramText.cpp -o histogramText `pkg-config --cflags --libs opencv4`
./histogramText
```
* 결과값:
```
Histogram...
0 : 0
1 : 0
2 : 0
3 : 0
4 : 0
...
...
96 : 464
97 : 430
98 : 431
99 : 409
100 : 309
101 : 315
...
...
252 : 0
253 : 0
254 : 0
255 : 0
Sum of all frequency counts = 50625
rows * cols = 50625
```


* [histogramGraph.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramGraph.cpp) 컴파일 & 실행하기  
```
cd OpenCV_On_JetsonNano/09_Image_Histogram

g++ -ggdb histogramGraph.cpp -o histogramGraph `pkg-config --cflags --libs opencv4`
./histogramGraph
```

![histogramGraph.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/09_Image_Histogram/histogramGraph.png)
