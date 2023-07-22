# Google-Chromebook-Pixel-2015-Linux
details of converting my Google Chromebook Pixel 2015 to run Linux
1. install UEFI firmware (https://mrchromebox.tech/) 
2. install a range of Linux distros to find the major problem is the Broadwell audio.... (Slackware works, but not right)
3. Install Alpine Linux
   - download the 'Extended x86_64' this has the WiFi drivers
   - install using sys mode
   - make sure to add the user
   - once rebooted add additional software
   - https://wiki.alpinelinux.org/wiki/ALSA <= for sound and it works :)
   - https://www.youtube.com/watch?v=eJa_0M6kvO0 <= followed this but didn't install the extra apps
4. things not right
   - key mapping
   - on wake up black box on cursor (does go away after moving mouse
5. as root 'apk add git'
6. as root 'apk add flatpak'
8. as root 'flatpak install flathub com.vscodium.codium'
9. as root 'apk add docker'
10. as root 'apk add udisks2 udisks2-doc
11. add a theme (https://b00merang.weebly.com/)
12. 
