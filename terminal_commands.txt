Basic linux terminal commands cheat sheet


Note: * = Can be done without using the terminal.
Note2: Directories in windows terms are your folders. Whenever you see or hear the word directory, know it is just your folder/folders.
Note3: Software Manager is where you would install most programs and packages.


-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-


Basics:


shutdown now | Shuts down your computer. *

reboot | Reboots your computer. (Turns off then back on) *


cd <path> | Takes you in your terminal to the folder/location you specify. | Example: cd Desktop/Projects/ (Will take me into the Projects folder on my desktop. cd Desktop will just take you to the desktop.)


cp <file_name> <path/location> | Example: cp file.txt /home/ori/Desktop/Projects | This will copy file.txt on my desktop or in the folder I am currently in, and paste it into the folder named Projects on the desktop. (copy and paste function) *
Commands on how to move files and folders to different places can be found here: https://linuxhandbook.com/mv-command/


ls | ls just shows you what files and programs are in the folder you are currently in.


touch <filename> | Creates files in the current folder/directory you are in. Example: touch helloworld.txt (any extension) *


rm <options> <file/folder> | rm removes/deletes the specified file or folder. | Example: rm helloworld.txt | rm -r Desktop/Projects (If you don't want to do it using your mouse and moving it to the trash.) *


sudo <command> | Sudo runs files/programs/commands as "administrator" in windows terms. (I personally use doas)


-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-


important apt commands:

sudo apt update | Updates your systems packages and keeps things up to date, run this before installing stuff using apt.

sudo apt upgrade | Upgrades files, programs, and packages to newer versions.
This one cheeky command updates and upgrades your system. sudo apt update && sudo apt upgrade -y 

sudo apt install <package name> | Installs packages/programs. Just replace the <package_name> with the desired package. And suppose you want to install mplayer. That command will look like this sudo apt install mplayer  *

sudo apt purge <package_name> | Uninstalls/removes the package(s) that you specify. | Example: sudo apt purge mplayer
apt remove does the same but just removes normal stuff an leaves residue configuration. (purge is better) *



More about apt can be found here: https://itsfoss.com/apt-command-guide/
More about uninstalling stuff can be found here: https://averagelinuxuser.com/uninstall-software-linux-mint/


-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-=-


Made by - Ori -
