First, To change your password go to /pcmdp-pp/bin and change the file inside. Make "default" into whatever password you want. DO NOT REMOVE THE QUOTATION MARKS. PLACE YOUR PASSWORD INSIDE THEM. Afterwards, Continue to step 2.

Open iexpress as Administrator, And use the pcmdp-iexpress-packager.SED file, And modify it. Only touch the included files, And the target for the file to be placed. Remove all the included files, And then set the included files to "sethc.bat" and "cmdpasswordscript". If it already shows both, Still do it. Otherwise step 3 wont work.
Set the target to the sethc-pcmdp folder, With the filename "sethc.exe". Afterwards, Continue to step 3.

Open iexpress as Administrator again, And use the pcmdp-iexpress-packager.sed file included. Backup C:/Windows/System32/sethc.exe by renaming or copying it. Place the new file inside the folder and place the pcmdp-pp folder with it. Just use the sticky keys shortcut (Needs to be enabled) to use pcmdp.