# HoloISO Hotfix - A Hotfix script for [HoloISO](https://github.com/HoloISO/holoiso) Issues.

\- **THIS SCRIPT HAS BEEN CODED TO ENSURE THAT YOUR SYSTEM WON'T GET BORKED, BUT IS STILL EXPERIMENTAL. PROCEED AT YOUR OWN RISK.**

<br/>If this does not work for you, please tell me what happens by opening an [Issue](https://github.com/C7YPT0N1C/HoloISOHotfix/issues/new)!

<br/>**INSTRUCTIONS:**

\- Boot into Holoiso Desktop Mode

\- At this point, Steam Desktop will boot up. You may sign in, but this will skip the SteamOS OOBE. I do recommend to sign in, but if you want / need the OOBE, don't sign in.

\- Open a web browser and download the script above.

\- Extract download.

\- Open folder, right click empty space, and click "Open Terminal Here"

\- In the terminal that appears, run: 
<br/>`sudo su`
<br/>then
<br/>`sudo bash ./HoloISOHotfix.sh`

\- When the script has finished running, reboot, as "return to game mode" seems to be hella buggy.

<br/>**NOTES:**
<br/>\- You may have to reboot your device a few times for the OS to fully boot up. If a kernel doesn't work, try a different one.
<br/>\- This hotfix script will be updated if a new hotfix is found. Please re-download and run the new script to patch HoloISO.
<br/>\- Please keep in mind that when the script runs, mesa-amber will be installed to replace mesa, mesa and mesa-amber both being the 3d graphics library Holoiso / SteamOS use. You can switch to any version of mesa, and see if that works better for you.
<br/>\- Please keep in mind that this script *may* have unintended side effects if you have more than 1 user on your system (?).

<br/>[View Full Project Plan](https://github.com/users/C7YPT0N1C/projects/4/views/3?sortedBy%5Bdirection%5D=asc&sortedBy%5BcolumnId%5D=Status)
<br/>You can use the (Deprecated) [Gist](https://gist.github.com/C7YPT0N1C/5625ef6a40a558ed6584b6ed62a66419). You can also view the [CHANGELOG](/CHANGELOG).
