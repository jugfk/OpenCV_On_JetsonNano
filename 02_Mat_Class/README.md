## Mat 객체(Objects) 선언하기
***

* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* Mat_colors.cpp 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/02_Mat_Class
g++ -ggdb Mat_colors.cpp -o Mat_colors `pkg-config --cflags --libs opencv4`
./Mat_colors.cpp
```


* splitColorChannels.cpp 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/02_Mat_Class
g++ -ggdb splitColorChannels.cpp -o splitColorChannels `pkg-config --cflags --libs opencv4`
./splitColorChannels
```
