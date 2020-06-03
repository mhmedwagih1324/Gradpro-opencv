# Gradpro-opencv
### This installation is intended for opencv v4 on conda
## installing the environment
1. install [conda](https://www.anaconda.com/products/individual#Downloads).
2. open Anaconda Prompt from the start menu.
3. create new environment through the command: `conda create --name py37 python=3.7`
4. Activate the environment through the command: `activate py37`
5. install numpy through the command: `conda install numpy`
6. install opencv through the command: `conda install opencv`
### check your installation
1. open Anaconda prompt again and activate py37 environment as steps 2 & 4 in installation
2. type `jupyter-notebook` in the prompt.
3. from the top right corner, click `new` and choose `Python 3`
4. type in the first cell the following code:  
```
import cv2 as cv
print(cv.__version__)
```
5. if no error appears then you're good to go 👏.
