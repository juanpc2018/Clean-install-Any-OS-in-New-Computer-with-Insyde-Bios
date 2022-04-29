# Clean-install-Any-OS-in-New-Computer-with-Insyde-Bios
Secret / Hidden Cltr+S SATA Menu

New computers with intel Optane + Insyde Bios,
cannot clean install any other OS, other than W10,

The Reasons:

A) intel Optane does Not have drivers for other OS,
Optane is like a CPU HW Raid.
without intel Drivers other OS cannot detect the main M.2 NVMe drive.

B) Insyde Bios has a Secret / Hidden Menu, 
does Not allow to Dissable SATA Optane.

The Sollution:
press Ctrl+S in Advanced,
The hidden SATA menu will appear like Magic.
and you can select Normal AHCI.
With AHCI UEFI is possible to install any other OS: 

Linux, Windows8.1 "my favorite Windows", etc...

the other problem is Touchpad drivers, Bluetooth , Wifi, Ethernet, etc...

New computers with Insyde Bios some have "Fake" RAM,
you buy 8GB,
remove screws and surprice, has 4GB of RAM stick, 
where are the other? Winmdows10 say it has 8GB of RAM,
BUT... 4GB are always busy doing Nothing...

the reason is because latest Intel RST with Optane SATA,
borrows 4GB of NVMe to fake 8GB of RAM.

it´s a Weird Fake RAM, Fake Optane.
or "Virtual RAM, Virtual Optane."

Real RAM is 4GB, some may call it Fake Advetisement.
does Not want Nobody to find out, thats why it has a Secret Menu in the Insyde Bios.

Anwyway...
Windows8.1x64 with Bing installs, but needs Updates and Drivers.

A System Image Restore cannot be done with Intel RSP with Optane Active in the Bios.
i only deleted the large partition, Not the Smaller, Not the Recovery...
and i made a W11 System image Backup to an external USB3.0 Before Deleting the Kingston 256GB M.2 drive.

IT WORKS !!!
but i almost got an aneurism in the process.

Hardware is Jail Free.
