# myarchinstall
i'm planning on using arch so of course i need to use commands so i'm documenting this on github so it will be easier 

Step 1 installing arch using iso from arch website and using archinstall command so i don't have to go though the disk commands 
make sure to use LTS kernal cause i'm running a older pc (rx 7600 and a ryzen 5700X) maybe install recent just in case
and make sure to install the network part

Step 2 after everything is installed first download flatpak using sudo pacman -S flatpak 
and download Gnome Boxes through flatpak cause of some bug causing it to not work after having everything installed
and download aur using SomeOrdinaryGamers video 
https://youtu.be/-GyOFlWs4HY?feature=shared&t=1635

also to customize it so something like kdewallet stops popping up here's some helpful guides 
Startup with nothing opened: https://forum.manjaro.org/t/restart-shut-down-and-resume-from-sleep-dont-work/170282/4

Auto log in: https://forum.manjaro.org/t/automatic-login-on-off/168182 

Disable kdewallet https://www.youtube.com/watch?v=pzpPBTlmnco&t=28s

before downloading aur here's how to download browsers (use ones that don't require aur or yay)

Step 2.5 Browsers
Brave: yay -Sy brave-bin 

librewolf : (need yay) yay -s librewolf or yay -s librewolf-bin

Firefox sudo pacman -s firefox

Chromium sudo pacman -S chromium

Step 3 GAMES and add ons 

Steam:
https://www.xda-developers.com/how-run-steam-linux/#installing-steam-on-arch-linux-and-arch-based-distros

lutris : sudo pacman -s lutris or just use flatpak

Minecraft use the other distribution download button 

Clone hero just install like a appimage

STEP 3.5 GAME ADD ONS 

Mangohud use releases on github and use ./mangohud-setup.sh install command

Goverlay use appimage or pacman -S goverlay

Step 4 other stuff

Discord use flatpak unless someone wants to use the tar file

Video editors: kdenlive and shotcut use appimage or flatpak don't know commands and but both editors flatpaks versions i've had problems with 

Libreoffice sudo pacman libreoffice-fresh or libreoffice-still (fresh is what windows version has)

Protonvpn use flatpak unless there's another way on arch to use it 

Timeshift Yay -S timeshift

GIMP use flatpak or appimage








