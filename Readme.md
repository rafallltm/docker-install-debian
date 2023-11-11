# Docker via apt no Debian Linux 6.1.0-13-amd64 (2023-09-29) x86_64 GNU/Linux

configure o sudo para dar poderes de super vaca ao user:

#apt install sudo

#sudo visudo

add a linha do user em baixo da linha do root no arquivo /etc/sudoers : 

root ALL=(ALL:ALL) ALL

seu_user ALL=(ALL:ALL) ALL

add o user ao grupo sudo:

$sudo usermod -aG sudo seu_usuario

rode o script:

$chmod +x install.sh

$./install.sh

$sudo reboot

$sudo apt install docker-compose

