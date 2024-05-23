# Detecting-lines
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FMingHieu%2FDetecting-lines.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FMingHieu%2FDetecting-lines?ref=badge_shield)

 Detection of lines using opencv and python.
 This Initial system shows basic concepts of machine vision in assisted driving.The code is free to be used and        modified  by anybody who wishes to do so.
 - Video results: [Detecting Lines Opencv Python ](https://www.youtube.com/watch?v=IkkdvRMW7R8&t=241s)
 
# UTPL

#Professor:
- Rodrigo Barba        [lrbarba@utpl.edu.ec](mailto:lrbarba@utpl.edu.ec)

#Student:
- Jonas Carrillo       [jonascs1692@gmail.com](https://mail.google.com/mail/?tab=wm#inbox)

#System Requirements
- An i3 or better processor. The faster the better, especially at high video resolutions.
- 2 GB or more RAM.
- At least 100 MB Free Disk space
- Windows 7 or later, OS X 10.8 or later (has only been tested on 10.9), Linux 3.0+

# Installation
First you must install the following libraries on your computer

   - [OpenCV](http://opencv.org/) version 2.4.10+ 
   - [Python](https://www.python.org/) 2.7.10 (or any later Python 2.x) ([See Installation on OS X if using a Mac](#installation-on-os-x)) 
   - [Numpy](http://www.numpy.org/) 1.8.0 (or any later Numpy)  

#Installation on OS X
Apple uses a prior version of Python that does not support the latest Python libraries. One work around is to install Python with Homebrew:

`$ brew install python`

Replacing Apple's system Python with an unsupported version may break things. Therefore we linked Homebrew's Python into the system path without replacing the system Python:

`$ ln -s /usr/local/Cellar/python/2.x.y/bin/python /bin/hbpython`

Where 2.x.y is the version number of your Python.

#Running the code in Linux
------------
Instructions to run the code from linux console

1.  Open Terminal 
2.  Write the path of our .py file, in my case `cd Documentos/Data/`==>Press Enter
3.  Writhe `ls` ==>Press Enter  the following files are displayed in console " DETECTION OF LINES.xlsx  Detect_Lines_day.py  Detect_Lines_night.py  README.txt  videos"
4.  Write the full name of the .py file as follows.                                                                       example: `python Detect_Lines_day.py`
5.  PRESS ENTER AND RUN THE PROGRAM


------------




## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FMingHieu%2FDetecting-lines.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FMingHieu%2FDetecting-lines?ref=badge_large)