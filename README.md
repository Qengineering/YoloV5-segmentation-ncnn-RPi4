# YoloV5 segmentation Raspberry Pi 4
![output image]( https://qengineering.eu/github/Parking_seg_n.webp )
## YoloV5 segmentation with the ncnn framework. <br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
Special made for a bare Raspberry Pi 4, see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html)

------------

## Benchmark.
| Model  | size | objects | mAP |  RPi 4 64-OS 1950 MHz |
| ------------- | :-----:  | :-----:  | :-------------:  | :-------------: |
| YoloV5n | 640x640 nano| 80 | 28.0 | 1.4 - 2.0  FPS |
| YoloV5s | 640x640 small| 80 | 37.4 | 1.0 FPS | 
| YoloV5l | 640x640 large| 80 | 49.0 | 0.25 FPS | 
| YoloV5x | 640x640 x-large| 80 | 50.7 | 0.15 FPS |
| [Yoact](https://github.com/Qengineering/Yolact-ncnn-Raspberry-Pi-4) | 550x550 | 80 | 28.2 | 0.28 FPS |

------------

## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 32 or 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. [Install 64-bit OS](https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. [Install ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. [Install OpenCV 4.5](https://qengineering.eu/install-opencv-4.5-on-raspberry-64-os.html) <br/>
- Code::Blocks installed. (```$ sudo apt-get install codeblocks```)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/YoloV5-segmentation-ncnn-RPi4/archive/refs/heads/main.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip, LICENSE and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm LICENSE <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
parking.jpg <br/>
busstop.jpg <br/>
YoloV5-seg.cpb <br/>
main.cpp <br/>
yolov5n-seg.bin <br/>
yolov5n-seg.param <br/>
yolov5s-seg.bin <br/>
yolov5s-seg.param <br/>

------------

## Running the app.
To run the application load the project file YoloV5-seg.cbp in Code::Blocks. More info or<br/> 
if you want to connect a camera to the app, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/><br/>
Many thanks to [FeiGeChuanShu](https://github.com/FeiGeChuanShu)!<br/><br/>
![output image]( https://qengineering.eu/github/Busstop_seg_n.webp )

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 

