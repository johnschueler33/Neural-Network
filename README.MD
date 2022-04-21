#!/usr/bin/env python3
# -*- coding: utf-8 -*-
 
 
 INSTRUCTIONS FOR RUNNING CODE
(unable to ship code without user manually altering the following code)

DIRECTIONS START
 
 pip install pafy
 
 pip install youtube-dl
 or
 pip install youtube_dl
 
 pip install torch
 
 pip install torchvision

 pip install opencv_python

** run FinalProj_newfootage.py **

The following error should return:



  File "C:\Users\49896\anaconda3\lib\site-packages\pafy\backend_youtube_dl.py", line 54, in _fetch_basic
    self._dislikes = self._ydl_info['dislike_count']

KeyError: 'dislike_count'




** control click on "C:\Users\49896\anaconda3\lib\site-packages\pafy\backend_youtube_dl.py"
and open the file.**

** in the the new file, backend_youtube_dl.py, delete line 54:
self._dislikes = self._ydl_info['dislike_count']       and save file**

** return to main file, FinalProj_newfootage.py and run the final. The file
should now run properly. A video titled video3.avi should save which shows
an output with what the seucrity camera footage will look like after 
having been run through our model**