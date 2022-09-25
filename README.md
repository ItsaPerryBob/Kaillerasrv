# Kaillerasrv
Kaillera from http://www.kaillera.com/
Rights from the coder at kaillera.com, only researching this project.

To use kaillerasrv u need to do these commands in Ubuntu:
sudo dpkg --add-architecture i386
sudo apt-get update
sudo apt-get install libncurses5:i386 libstdc++6:i386 zlib1g:i386

before
Type in "ls" (no quotes) and hit enter. Hopefully you're going to see kaillerasrv.tar.gz. If so, go to the next step. If not, try and download it again. (Alternatively, you can download it to your local computer, then use an ftp program to transfer it to your shell.)

Type "tar -zxf kaillerasrv.tar.gz" and hit enter. You should now have a few more files in your home directory.

Next, type "chmod +x kaillerasrv" and hit enter.

Finally, type "./kaillerasrv" and hit enter. You'll see some stuff about touching the master server and so on. Congrats! Your server is working.

