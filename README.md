# Clean-install-Any-OS-in-New-Computer-with-Insyde-Bios
Secret / Hidden Cltr+S SATA Menu

New computers with intel Optane + Insyde Bios,
cannot clean install other OS, Only W10.

The Reasons:

A) intel Optane does Not have F6 drivers for other OS,
Optane is a CPU HW Raid, 
without Drivers, other OS cannot detect the Optane RAID M.2 drive.
Normal Optane appears as separated NVMe M.2 drive, and CPU join both drives,
but this is Not a Normal Optane, Bios disables completely the Optane memory, 
also in Normal Optane, when you dissable the Optane, MAin drive Boots ok.
This does Not.
the question is why?

B) InsydeH2O Bios has a Secret / Hidden Menu, 
does Not allow to Dissable Intel Optane by Factory Default.

The Solution:
Enter UEFI Bios by pressing [F2] in Boot,
or in Advanced Windows Starttup, UEFI configuration option.
inside the UEFI go to [Advanced] Tab,
and press Ctrl+S

The hidden SATA menu will appear like Magic.
and you can select Normal [AHCI] or [Intel RST with Optane]
With AHCI UEFI Active is possible to install any other OS: 

Linux, Windows8.1 "my favorite Windows", etc...

the other problem is Drivers for Touchpad, Bluetooth, Wifi, Ethernet, etc...

Newer computers with Insyde Bios, some have "Fake" RAM,
you buy 8GB,
remove the screws and surprice, has 1x 4GB RAM stick,
maybe sticker has label Wrong?
but if sticker is right, and has only 4GB of RAM,
where are the other 4GB? Winmdows10 say it has 8GB of RAM,
BUT... 4GB are always busy doing Nothing in W10 & W11, Dr.strange..
That was one of the reasons i decided to upgrade W10 to W11, and Delete W11.
in W8.1 also shows 8GB of RAM, mmm mystery...
but memory usage is normal: 0.8 GB
Now i can install AMD DataRam Ramdisk RamDrive for Temp folder.

CPU-Z shows 1x stick of 4GB.
where are the other 4GB ?
unknwonw.
maybe...
Insyde UEFI Bios seems to borrow 4GB of NVMe to fake 8GB of RAM, 
Kingston 256GB M.2 shows 237GB Total, 221GB Free after Win8.1 Clean install.
has a 1GB Recovery Partition "1024MB".

Disk Manager shows: 238.46 GB Online.
100MB, 237.36GB NTFS GUID GPT 244182MB 1MB unallocated, 100MB Reserved space.

or has another 4GB soldered on the other side of the PCB?

it´s Weird "Fake" RAM, "Fake" Optane.
or "Virtual" RAM, "Virtual" Optane.

Real RAM is 4GB, some may call Fake Advertisement.
Seems the other 4GB appears out of thin air.
i dont know where they are, unless i do a complte ifixit teardown to see the other side of the board.

Anyway... 
If you do Not Activate the Secret SATA Menu in the Bios,
its impossible to install other OS,
they want you to use Windows10, 
like twisting your arm in Karate, TaeKwonDo, Judo, Jujitsu, etc...
thats why it has a Secret Hidden Menu.

Anwyway...
Windows8.1x64 with Bing installs, but needs Updates and Drivers.

A System Image Restore cannot be done with [Intel RSP with Optane] Active in the Bios.


To install i deleted the large partition only, 
Not the Smaller, Not the Recovery...
and made a System image Backup Before, to an external USB3.0 drive.
Before Deleting the large partition in the factory M.2 drive.

Now IT WORKS !!!
but i almost got an aneurysm in the process.
and got banned in the answers.microsoft.com website too.

But Hardware is Jail Free.
Nobody is twisting my arm, i can install what ever OS i want.
