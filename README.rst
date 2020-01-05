
Install dependecies::

   $ pip3 install -r r2.txt

Usage
=====

First of all you have to train face recognizer how your face looks like.
Then you can test it with demo command.

Training
========

::

    $ python facerecognition/main.py train

This command will take 10 pictures using your webcam.
Press any key after every shot to take a new one.

Demo
====

To test face recognition use the demo that captures view from your webcam
and recognizes faces in realtime::

    $ python facerecognition/main.py demo

Requirements
============

* NumPy
* OpenCV 3
* matplotlib
* PIL - Python Imaging Library
* Python 3

