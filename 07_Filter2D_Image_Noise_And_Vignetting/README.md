# Filter2D, 이미지 노이즈, 그리고 비네팅
***
* 다운로드하기
```
git clone https://github.com/jetsonworld/OpenCV_On_JetsonNano.git
```

* [filter2D.cpp](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/07_Filter2D_Image_Noise_And_Vignetting/filter2D.cpp) 컴파일 & 실행하기
```
cd OpenCV_On_JetsonNano/07_Filter2D_Image_Noise_And_Vignetting
g++ -ggdb GaussianKernels.cpp -o GaussianKernels `pkg-config --cflags --libs opencv4`
./GaussianKernels
```
![GaussianKernels.png](https://raw.githubusercontent.com/jetsonworld/OpenCV_On_JetsonNano/master/06_Gaussian_function_and_filtering/GaussianKernels.png)

