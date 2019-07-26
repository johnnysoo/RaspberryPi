# Science Walden Project

설치된 OS "2019-07-10-raspbian-buster-lite"
Win32DiskImager를 통해 OS를 라즈베리 파이에 설치 후 아래 과정을 수행하도록 한다.<br/>
<br/>

#### 0. Wi-Fi Connect

OS가 설치된 micro SD 카드에 SSH 파일과 wpa_supplicant.conf 삽입
<br/><br/>
  
#### 1. Package Update

    > sudo apt-get update

    > sudo apt-get upgrade

    > sudo pip3 install --upgrade setuptools

if above doesn't work try

    > sudo apt-get install python3-pip  
<br/>

#### picamera installation

    > sudo apt-get install python-picamera
<br/>

#### Neopixel installation

You'll need to install the Adafruit_Blinka library that provides the CircuitPython support in Python.
This may also require verifying you are running Python 3.

    > sudo pip3 install adafruit-circuitpython-neopixel

&#35; if you use python3 may be using 'pip'
then, you can use import board & import neopixel
