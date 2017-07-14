## Opencv installation.

We are going to use for this class Python 3.5 version and opencv 3.2 Included in pip

#### Required packages.
- OpenCV
- Numpy
- Matplotlib
- Jupyter

## Windows.

#### Download WinPython.
I found this the easiest approach to install python and the required libraries (except for opencv).
https://sourceforge.net/projects/winpython/files/WinPython_3.5/3.5.3.1/
Choose Qt option depending on your computer architecture.

#### Install opencv
Using the *Winpython Command Prompt* you are able to use pip directly to install packages from PyPI:
```sh
pip install opencv-python opencv-contrib-python
```

## Linux (Tested with debian and similar).

### Install Python3
```sh
sudo apt-get install python3 python3-virtualenv
```

#### Install and create virtualenv
```sh
$ virtualenv --no-site-packages --python=/usr/bin/python3 dip/
$ source dip/bin/activate
```

#### Install packages
```sh
$ pip install numpy matplotlib opencv-python opencv-contrib-python jupyter
```

## Mac

#### Homebrew installation.
Refer to http://brew.sh/index_es.html for instructions

#### Python3 installation.
```sh
$ brew install python3 pip
$ pip install virtualenv
```
#### opencv and libraries installation.
```
$ virtualenv --no-site-packages --python=/usr/local/bin/python3 dip/
$ source dip/bin/activate
$ pip install numpy matplotlib opencv-python opencv-contrib-python jupyter
```
