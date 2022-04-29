# Clean-install-Any-OS-in-New-Computer-with-Insyde-Bios
Secret / Hidden Cltr+S SATA Menu

New computers with intel Optane + Insyde Bios,
cannot clean install any other OS, other than W10,

The Reasons:

A) intel Optane does Not have drivers for other OS,
Optane is like a CPU HW Raid.
without Drivers other OS cannot detect the main M.2 NVMe drive.

B) Insyde Bios has a Secret / Hidden Menu, 
does Not allow to Dissable SATA Optane.

The Solution:
Enter BIOS UEFI pressing F2 in Boot,
or in Advanced Windows Starttup, UEFI config option.
inside the UEFI, go to Advanced,
and press Ctrl+S

The hidden SATA menu will appear like Magic.
and you can select Normal [AHCI]
With AHCI UEFI is possible to install any other OS: 

Linux, Windows8.1 "my favorite Windows", etc...

the other problem is Touchpad drivers, Bluetooth, Wifi, Ethernet, etc...

Newer computers with Insyde Bios some have "Fake" RAM,
you buy 8GB,
remove the screws and surprice, has 1x 4GB RAM stick,
maybe sticker is labeled Wrong?
but if sticker is right, and its true 4GB of RAM,
where are the other 4GB? Winmdows10 say it has 8GB of RAM,
BUT... 4GB are always busy doing Nothing in W10 & W11...

in W8.1 with RST Optane disabled, shows 8GB of RAM also, mystery.
but memory usage is normal / low: 0.8 GB

using CPU-Z shows 1x stick of 4GB.
where is the other 4GB ?

maybe...
the reason seems the Insyde UEFI Bios borrows 4GB of NVMe to fake 8GB of RAM.
or has another 4GB soldered on the other side of the PCB?

it´s a Weird "Fake" RAM, "Fake" Optane.
or "Virtual" RAM, "Virtual" Optane.

Real RAM is 4GB, some may call Fake Advertisement.
Seems the other 4GB appear out of thin air.
i dont know where they are.

Anyway... 
If you do Not Reveal the Secret SATA Menu in the Bios,
is impossible to install other OS,
they want you to use Windows10 
like twisting your arm in Karate, TaeKwonDo, Judo, Jujitsu, etc...
thats why it has a Secret Hidden Menu in the Bios.

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
Nobody is twisting my arm, anymore.
i can install what ever OS i want.
