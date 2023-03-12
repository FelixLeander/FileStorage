Thank you for commissioning me!
https://github.com/FelixLeander
discordapp.com/users/536544797997924362

The Solution contains 4 Projects, 2 of them are for the old '.NET Framework 4' to '.NET Framework 4.8' so it can run on Windows 7.
These two end with Win7 in their names.
The other two are for Windows 8 and above, using '.NET 6'.

The Projects 'FlandersIniWatcher' create a config.txt file when started in the CommonApplicationData which normally is 'C:\ProgramData' (this folder is invisible).
The first line in the config file should point to the .ini file 'C:\PathTo\file.ini'.
The second line is the password you need to enter to get rid of the blocker window.
The third line is the key, which you'll need to provide, so the software is working. You will get the key from me.
If the program is running, you should see a blue, white icon in the system tray (bottom right).
Now if the .ini file values 'cooltime' is changed under 30000 a BlockerWindow will pop up which can't be closed until the password is entered. Also, these value changes are logged.
If the program is started with any arguments, it will display the BlockerWindow after startup.

The 'ProcessWatcher' needs two arguments, if non is given it simply ends:
First How often it will look for the process to be running, minimum 1000 (every 1 second).
Second is the path of the .exe, which it then starts.
The program will start the .exe without arguments when started, but when detecting the process is not running, it will start it with the argument 'true'.

If there are any errors with my program, please contact me, I'll be glad to fix them!

Side Note:
If you search for '.NET' try 'dotNET' instead.