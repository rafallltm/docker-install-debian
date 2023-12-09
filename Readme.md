# Docker via apt no Debian 6.1.55-1 (2023-09-29) x86_64 GNU/Linux


configure o sudo para dar poderes de super vaca ao user:

#apt install sudo

#sudo visudo

add a linha do user em baixo da linha do root no arquivo /etc/sudoers : 

root ALL=(ALL:ALL) ALL

seu_user ALL=(ALL:ALL) ALL

add o user ao grupo sudo:

$sudo usermod -aG sudo seu_usuario

instale o curl: 

$sudo apt install curl

rode o script:

$chmod +x install.sh

$./install.sh


