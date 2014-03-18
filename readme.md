##LegacyPostInst

Securely update the MacPro1,1 or MacPro2,1 which is using the EFI hack to run OS X 10.8 or above.

This requires a mac which is already successfully running with the EFI hacks (and appropriate kext replacements too).

##### install instructions:

Open a terminal and run the ```lpostinst``` bash script.

Download the required update from apple's download site (either the combo or standard), run the update package until it asks you to restart.

Ignore the installer, **DO NOT RESTART**, and open the file ```/Library/Updates/[numbers]/Upd[numbers].pkg``` and follow the install instructions. You're now installing the new update without requiring a restart.

When the installer has finished, again, **DO NOT RESTART**, and remove the contents of ```/Library/Updates``` continue following the instructions in the terminal window until it has completed.

You can now force quit the Installer application and restart your computer. It will ask if you want to restart and install updates or just restart, choose the **restart** option and allow the computer to reboot.
