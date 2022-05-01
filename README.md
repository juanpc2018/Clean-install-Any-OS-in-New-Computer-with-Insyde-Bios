# Clean-install-Any-OS-in-New-Computer-with-Insyde-Bios
Secret / Hidden Cltr+S SATA Menu

New computers with intel Optane + Insyde Bios,
cannot clean install other OS, Only W10.

The Reasons:

A) intel Optane does Not have F6 drivers for other OS,
Optane is a CPU HW Raid, 
without Drivers, other OS cannot detect the Optane RAID M.2 drive.

Normal Optane appears as separated NVMe M.2 drive, and CPU join both drives,
but this is Not Normal Optane, Bios disables completely the Optane memory, 
also in Normal Optane, when disable Optane, Main drive Boots ok.
This Optane Not.
the question is why?

B) InsydeH2O Bios has a Secret / Hidden Menu, 
does Not allow to Disable Intel Optane.

The Solution:
Enter UEFI Bios by pressing [F2] in Boot,
or in Advanced Windows Startup, UEFI configuration option.
inside the UEFI go to [Advanced] Tab,
and press Ctrl+S

The hidden SATA menu will appear like Magic.
and you can select between Normal [AHCI] or [Intel RST with Optane]
With AHCI UEFI Active is possible to install any other OS: 
M.2 or SSD is detected Normal.

in AHCI is possible to install Linux, Windows8.1 "my favorite Windows", etc...

other problem is Drivers for Touchpad, Bluetooth, Wifi, Ethernet, etc...
Linux Kernet 5 has most drivers built-in.

Newer computers with Insyde Bios, some have "Fake" RAM,
example: you buy 8GB,
remove the screws and surprise, has 1x 4GB RAM stick,
maybe sticker has label Wrong?
but if sticker is right, and has only 4GB of RAM,
where are the other 4GB? Winmdows10 say it has 8GB of RAM, same as W11
BUT... 4GB are always busy doing Nothing, Very strange.

That was one of the reasons i decided to upgrade W10 to W11, and Delete W11.
in W8.1 also shows 8GB of RAM, a mystery...
but memory usage is normal: 0.8 GB
Now i can install AMD DataRam Ramdisk RamDrive for Temp folder.

CPU-Z shows 1x stick of 4GB.
where are the other 4GB ?
unknown.
maybe...
Insyde UEFI Bios seems to borrow 4GB of NVMe to fake 8GB of RAM,?
Kingston 256GB M.2 shows 237GB Total, 221GB Free after Win8.1 Clean install.
has a 1GB Recovery Partition "1024MB".

Disk Manager shows: 238.46 GB Online.
100MB, 237.36GB NTFS GUID GPT 244182MB 1MB unallocated, 100MB Reserved space.

or has another 4GB soldered on the other side of the PCB?

it´s Weird.

Real RAM 1x4GB,
the other 4GB appears out of thin air.
i dont know where they are, unless i do a complete ifixit teardown to see the other side of the board.
in the mean time i have 2 theories:
RAM is slowed, and split with interrupts, like Cores into Threads.
or RAM is .zip .rar .7zip in HW by Insyde Bios or CPU Memory controller.
if there is Not 4GB of Ram soldered to the other side of the PCB.
easy to know, if i remove the 4GB stick, it should boot ok, if has 4GB soldered somewhere.
or
$ sudo lshw -short
/0/d                                 memory         8GiB System Memory
/0/d/0                               memory         4GiB SODIMM DDR4 Synchronous 3200 MHz (0,3 ns)
/0/d/1                               memory         4GiB SODIMM DDR4 Synchronous 2667 MHz (0,4 ns)


Anyway... 
If you do Not Activate the Secret SATA Menu in the Bios,
its impossible to install other OS,
they want you to use Windows10, 
like twisting your arm in Karate, TaeKwonDo, Judo, Jujitsu, etc...
thats why it has a Secret Hidden Menu.

With Optane Disabled, 
Windows8.1x64 with Bing installs, but needs Updates and Drivers.
A Win8.1 System Image Restore cannot be done with [Intel RSP with Optane] Active in the Bios.

Windows10 OEM license cannot be Downgraded to 8.1,
works up W11, but Not Down to W8.1
Only Full Retail license can be Downgraded.

To install Win8.1 i deleted the large partition only, 
Not the Smaller, Not the Recovery...
and made a System image Backup Before, to an external USB3.0 drive of W11,
Before Deleting W11 large partition in the factory M.2 drive.

but then decided to install Linux and deleted the whole M.2 drive.

IT WORKS !!!
but i almost got an aneurysm,
also got banned in the answers.microsoft.com website too.
But Hardware is Jail Free.
Nobody is twisting my arm anymore, i can install what ever OS i want.
