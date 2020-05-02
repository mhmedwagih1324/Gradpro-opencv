# Gradpro-opencv

## installing the environment
1. install [conda](https://www.anaconda.com/products/individual#Downloads).
2. open Anaconda Prompt from the start menu.
3. create new environment through the command: `conda create --name py27 python=2.7`
4. Activate the environment through the command: `activate py27`
5. install numpy through the command: `conda install numpy`
6. download [opencv2.4](https://sourceforge.net/projects/opencvlibrary/files/opencv-win/2.4.13/opencv-2.4.13.6-vc14.exe/download) (for windows)
7. install opencv by double clicking on the file that has been downloaded at the above step.
8. go to the directory where you've installed opencv and go to this directory: `opencv\build\python\2.7\x64`
9. copy the file `cv2.pyd`
10. go to the directory where you've installed Anaconda and go to this directory: `Anaconda\envs\py27\Lib\site-packages`
11. paste the file `cv2.pyd` here.
### check your installation
1. open Anaconda prompt again and activate py27 environment as steps 2 & 4 in installation
2. type `jupyter notebook` in the prompt.
3. from the top right corner, click `new` and choose `Python 2`
4. type in the first cell the following code:  
```
import cv2 as cv
sift = cv.SIFT()
```
5. if no error appears then you're good to go 👏.
