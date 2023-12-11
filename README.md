# APT repo for Acton

Install Acton via this apt repository:
```sh
wget -q -O - https://apt.acton-lang.io/acton.gpg | sudo apt-key add -
echo "deb http://apt.acton-lang.io/ bullseye main" | sudo tee /etc/apt/sources.list.d/acton.list
sudo apt-get update
sudo apt-get install -qy acton
```
