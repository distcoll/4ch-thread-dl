Simple scripts in Python 3 that download all attachments from a thread on 4chan.org to a folder.

Continuous:
Run this script to download all images from a thread continuously until the thread ends, checking for new posts every two minutes. If run a second time, will create a new folder and redownload everything.

Single:
Run this script to download all the images from a thread and then exit. If run a second time, will continue where it left off.

Both can be run with command line arguments or without, in which case the user will be prompted for board code and thread number.

Example run:
single g 47916419
