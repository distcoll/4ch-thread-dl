# 4ch-thread-dl
Image downloader for 4chan

<<<<<<< HEAD
Simple scripts in Python 3 that download all attachments from a thread on 4chan.org to a folder.

Continuous:
Run this script to download all images from a thread continuously until the thread ends, checking for new posts every two minutes. If run a second time, will create a new folder and redownload everything.

Single:
Run this script to download all the images from a thread and then exit. If run a second time, will continue where it left off.

Both can be run with command line arguments or without, in which case the user will be prompted for board code and thread number.

Example run:
single g 47916419
=======
Simple script in Python 3 that downloads all attachments from a thread on 4chan.org to a folder.
Can be run with command line arguments or without, in which case the user will be prompted for board code and thread number.
You can make this an executable file or run it with python3 (i.e., $ python3 4ch-thread-dl [board] [thread number]).

Example run:
$ ./4ch-thread-dl g 47916419
>>>>>>> 24de8c2bd9b6f614dfef023f4f1a73e12039e450
