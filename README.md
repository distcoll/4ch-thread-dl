# 4ch-thread-dl

Simple script in Python 3 that downloads all attachments from a thread on 4chan.org to a folder.

###Requirements
Python 3 installed along with the requests module (it can be installed with pip3)

##Usage
Run the script with the arguments of the board and thread number. Optionally, you can pass the --continuous flag to tell the script that you want to monitor the thread until 404.

##### Example run:
<code>$ ./4chdl g 39894014 [-c]</code>
