# VID-to-SCR-Lib
Python library for converting video files (currently .mp4) to .scr screensavers and back from .scr to video (currently .mp4).
# Original Author 
Development was started on March 28th, 2025, by Marcin Jacek Chmiel.
# Contributors 
As of now, there are no more contributors than the original author.
If you have any problems or suggestions, contact me: *martingonn-dev@outlook.com
# Requirements
To use scripts with the library, make sure you have ffmpeg installed. If not, install it from here: https://ffmpeg.org/download.html
  * If you want to use example.py, modify line 21 with your file path: 
    converter = Mp4ToScrConverter(ffmpeg_path="C:/ffmpeg/bin/ffmpeg.exe") #change to your file path
    * If you put ffmpeg folder into C:/ (your ffmpeg folder path is C:/ffmpeg/), you don't need to change anything.
# How to install
* Simply install it via "pip install VidToScr".
  # Manually:
    # Versions 1.0.0 and 1.1.1
      * run "python setup.py sdist bdist_wheel"
    # Versions from 1.1.2
      * run "python -m build"
# Future Additions
* add more formats (.webp, .mov, .avi, .wmv, .mkv)
* Simply update for later Python versions
* (maybe) compile for older versions
# Downloads
![GitHub All Releases](https://img.shields.io/github/downloads/Martingonn/MP4-to-SCR-lib/total)
