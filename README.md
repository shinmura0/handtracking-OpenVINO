# [Original](https://github.com/victordibia/handtracking)(Raspberry Pi 3)  
![gif1](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif1.gif "gif1")  
**1FPS**  

# handtracing-OpenVINO(Raspberry Pi 3 with NCS2)

![gif2](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif2.gif "gif2")  
**10~15FPS**  
![gif3](https://github.com/shinmura0/handtracking-OpenVINO/blob/master/images/gif3.gif "gif3")  
  

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

# Acknowledgment
Thank you very much for the following link.
+ https://github.com/PINTO0309/MobileNet-SSD-RealSense
+ https://github.com/victordibia/handtracking
