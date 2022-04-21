# Convert image-to-sound-using-python

Introduction
--------
This repo will help you get started on how you can get started with Optical character recognition (*OCR*) and speech synthesis in python by building a simple project that will be converting an image into an audible sounds, combining both **OCR** and **Speech synthesis** in one application



Getting started 
-----------------
In order to use this code, firstly clone the repo using **git** or download the zip file manually

```bash
$-> git clone https://github.com/Kalebu/image-to-sound-python-
$->cd image-to-sound-python-
$ image-to-sound-python--> python app.py
```

Dependancies 
-------------
In order to run this code you're supposed to have **pytesseract** and **google text to sound** libary installed
on your machine, you can just use *pip* command to this.

```bash
-> pip install pytesseract
-> pip install gTTS
-> pip install pillow
```

**Note**: Installing pytesseeract can be an issue sometimes, so there ways in which you could do this effectively, to see how I recommend you going through the stackoverflow question  article [How do I resolve a TesseractNotFoundError? ](https://stackoverflow.com/questions/50655738/how-do-i-resolve-a-tesseractnotfounderror)
.


How to run 
------------
By default the script will load an image with name **image.png** from its current directory
to change it adjust the it to be the your new image name.

<img src="sample.png" alt="sample" width="500"/>

Thanks to
-------------
[kalebu](https://github.com/Kalebu)


