# Filter2D, 이미지 노이즈, 그리고 비네팅
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [GaussianKernels.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/06_Gaussian_function_and_filtering/GaussianKernels.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/06_Gaussian_function_and_filtering
g++ -ggdb GaussianKernels.cpp -o GaussianKernels `pkg-config --cflags --libs opencv4`
./GaussianKernels
```
![GaussianKernels.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/06_Gaussian_function_and_filtering/GaussianKernels.png)

