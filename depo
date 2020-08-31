#!bin/bash
sudo apt install gnupg -y
echo "deb [arch=amd64] http://depo.aciklab.org/ onyedi main" | sudo tee /etc/apt/sources.list.d/acikdepo.list
sudo wget -qO - http://depo.aciklab.org/public.key | sudo apt-key add -
sudo apt update
