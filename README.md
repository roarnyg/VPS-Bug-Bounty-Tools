# VPS-Bug-Bounty-Tools

Script that automates the installation of the main tools used for web application penetration testing and Bug Bounty.

## Usage:
```bash

sudo -s

# Vent på at sudo kjøres før du limer inn:
apt update
apt install locate
apt install pip3
apt install python3-pip
apt install python-is-python3
apt install python-dev-is-python3
pip3 install --upgrade setuptools
pip install dnspython

wget https://go.dev/dl/go1.25.0.linux-amd64.tar.gz -P ~/Downloads/
cd ~/Downloads/
rm -rf /usr/local/go && tar -C /usr/local -xzf go1.25.0.linux-amd64.tar.gz
export PATH=$PATH:/usr/local/go/bin

apt install dos2unix

Kjør det over manuelt. Scriptet VPS-Bug-Bounty-Tools.sh er utdatert og lager trøbbel. Installer derfor alle tools manuelt. 
... men ReconFTW installerer de fleste tools!

https://github.com/six2dez/reconftw
