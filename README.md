# Ubuntu-18.04-LTS-Desktop-Bioic-Beavor
This repository is providing you with how to install or set Ubuntu with any version, but specifically version 18.04 LTS Desktop Bionic Beaver


First of all, you have to install Ubuntun 18.04 LTS-Desktop-Bionic Beavor by referred this website https://releases.ubuntu.com/18.04/

Once your download has been completed, if you are going to boot from USB flash drive (12GB or above recommended), first of all, you have to download application in order to make bootable USB stick as below step:

- To install Ubuntu desktop ISO into USB stick to create the installation media, which is etcher.balena.io
- The download base depends on the computation operating system that you are going to set up your USB (e.g. you are using a window to download this bootable USB flash, so you download with Windows version)
- After the USB flash is set up, you can plug that USB into your computer to set up your Ubuntu (Linux).
- Inside the installation, there are some more steps that you can choose based on the level of security you want to set up your Ubuntu, but I am not going to details about that.
- Now suppose your installation is finished, don't forget to update your Ubuntu by using this command
- sudo apt-get update
- You will prompted to enter your login password. This will check for updates and tell you if there are any that need applying.
- To apply any updates, type: sudo apt-get upgrade

** Also this repository is going to guide you on how to install qt creator on your Linux operating system which is using Ubuntu.

Below are basic instructions for installing Qt on Linux that work.

-> Install prerequisites
   You can write the command name as sudo apt-get install qtcreator as normally used in Ubuntu for the Linux operating system.
   *be note that qt is qtcreator is always has it based version that can let you to works with.
   to install Qt-based, you can be referred to this website download.qt.io/archive/qt/5.14/5.14.2/ and donwload the run file to your Ubuntu directory.
   Then, you just cd ~/Downloads to go to that directory.
   And type this command: chmod +x qt*.run to allow the permission for installation.
   After that, you have to just type ./qt*.run for installation.
