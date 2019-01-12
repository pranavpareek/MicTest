# MicTest
A simple microphone test application in java. This application is based off https://gist.github.com/fedor-rusak/2294168

Highlights:
* uses singleton pattern to get common buffer object, to ensure there is only one buffer object that is being used
* uses threads to record and play sound so that there is no audible pause

