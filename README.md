# Amazing_Face_Detection
CPU Real-time Amazing Face Detection
# Test steps
## step1
Download opencv_dll and put it to current directory [BaiDu Cloud](https://pan.baidu.com/s/14VIsF6PD6ktU7ctUh301wA)
## step2
Set parameters:
`Amazing_Face_Detection.exe test_type img_path`
```cpp
like:  Amazing_Face_Detection.exe image test.jpg  (for image)
or:    Amazing_Face_Detection.exe imgdir /img/path/test_imgs  (for imgdir)
or:    Amazing_Face_Detection.exe video test.avi  (for video)
or:    Amazing_Face_Detection.exe video 0  (for usbcam)
```
# Algorithm efficiency
| Image Size | min_size | CPU(i7-9700K) Speed/FPS | CPU(ARMv7 @1.4GHz) Speed/FPS |
|:------:|:------:|:------:|:------:|
| 320x240  | 16x16 | 6ms/166.7 |35ms/28.6| 12x12 |
| 640x480  | 16x16 | 23ms/43.5 |190ms/5.3| 12x12 |
| 800x600  | 16x16 | 42ms/23.8 |    -    | 12x12 |
# Test experience
If the image size is larger than `720p`, it is recommended to scale the image `below 720p`!
# Example result
![image](https://github.com/samylee/Amazing_Face_Detection/blob/master/result.jpg)
# Reference
https://blog.csdn.net/samylee
