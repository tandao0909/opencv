This repository describers my journey on learning OpenCV, based on the book Learning OpenCV 3: Computer Vision in C++ with the OpenCV library. 

The author's repository can be found at [this link](https://github.com/oreillymedia/Learning-OpenCV-3_examples).

Here is how you pass the compile flag to g++ in order to compile an opencv file properly:
```bash
g++ test.cpp -o test -I /usr/include/opencv2 -L /usr/lib -lopencv_core -lopencv_imgproc -lopencv_highgui -lopencv_imgcodecs -lopencv_videoio
```
The compile command assume that you want to compile test.cpp file and want to output test file.

I am using opencv 4.9.0 and run on Ubuntu 22.04.4 LTS.