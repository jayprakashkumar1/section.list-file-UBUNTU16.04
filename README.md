### sources.list-file-UBUNTU16.04
This same contents should be in sources.list file to be ERROR FREE on sudo apt-get-update.

Follow the instructions:

### open the terminal : $ ctrl+Alt + t
then open sources.list file in gedit :
### $ sudo -H gedit /etc/apt/sources.list

#### Now copy And Paste these below lines to the opened sources.list file :

deb http://archive.ubuntu.com/ubuntu/ xenial main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ xenial main restricted universe multiverse

deb http://archive.ubuntu.com/ubuntu/ xenial-updates main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ xenial-updates main restricted universe multiverse

deb http://archive.ubuntu.com/ubuntu/ xenial-backports main restricted universe multiverse
deb-src http://archive.ubuntu.com/ubuntu/ xenial-backports main restricted universe multiverse

deb http://security.ubuntu.com/ubuntu xenial-security main restricted universe multiverse
deb-src http://security.ubuntu.com/ubuntu xenial-security main restricted universe multiverse

deb http://archive.canonical.com/ubuntu xenial partner
deb-src http://archive.canonical.com/ubuntu xenial partner
