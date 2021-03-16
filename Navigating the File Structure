https://www.crucial.com/support/ssd-support/mx200-support

From this website we can download the Crucial MX200 MU05 Update.

We can then go to where we downloaded this .zip file and unzip it using the command: $ unzip MX200_MU05_Update.zip

This gives us a .iso file. We can decompress this file using 7zip and the command: $ 7z x MX200_MU05_Update.iso

This gives us four directories. The scratch, cde, and '[BOOT]' directories aren't very important but are somewhat interesting. What we are focused on is the boot/ directory.

If we go into the boot directory we see that we have a file called core.gz. This is the core of our firmware that has been compressed with gunzip. We can decompress the file with the command: $ gunzip core.gz

That should result in a file simply titled core that if we run file on we can see is an ASCII CPIO Archive. We can decompress this file using the cpio command and more specifically: $ cpio -iv < core.

This will dump the entirety of the file system into our current directory. 

Once we have all of the directories we can then proceed into our opt/ directory where we will see another directory titled firmware/ in which we find 1.bin which is the firmware file located within the main branch.
