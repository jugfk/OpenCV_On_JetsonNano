# 젯슨 나노에서 OpenCV 4.1 사용하기
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* myfile.cpp 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/mydirectory
g++ -ggdb myfile.cpp -o myfile `pkg-config --cflags --libs opencv4`
./myfile
```
