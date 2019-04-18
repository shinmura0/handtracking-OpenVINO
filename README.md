# [Original](https://github.com/victordibia/handtracking)
![gif1](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif1.gif "gif1")  
(Raspberry Pi 3)  
**1FPS**  

# handtracing-OpenVINO
![gif2](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif2.gif "gif2")
![gif4](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif4.gif "gif4")  
(Raspberry Pi 3 with NCS2)  
**10~15FPS**  

# Environment
+ Raspberry Pi 3(or PC)
+ USB camera
+ [NCS2](https://software.intel.com/en-us/neural-compute-stick) or Movidius

# How to use
+ Install OpenVINO
+ Download this repository
+ Command as follows

```
python3 main.py -wd 640 -ht 480
```

Click [here](https://qiita.com/shinmura0/items/07d976fc13ce774036b8) for details(Japanese)

# Acknowledgment
Thank you very much for the following link.
+ https://github.com/PINTO0309/MobileNet-SSD-RealSense
+ https://github.com/victordibia/handtracking
