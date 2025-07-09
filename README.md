# Instalar HOME ASSISTANT SUPERVISED con DOCKER. Rápido y Fácil.
```
sudo apt update
sudo apt upgrade
sudo apt install -y software-properties-common apparmor-utils avahi-daemon dbus jq network-manager
curl -sL "https://raw.githubusercontent.com/Kanga-Who/home-assistant/master/supervised-installer.sh" > supervised-installer.sh
chmod 777 supervised-installer.sh 
# ojo, el comando -m raspberry4 depende de tu equipo
./supervised-installer.sh  -m intel-nuc -d /docker/hassio/
clear
```