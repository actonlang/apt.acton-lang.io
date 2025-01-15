# APT repo for Acton

Install Acton via this apt repository:
```sh
sudo install -m 0755 -d /etc/apt/keyrings
sudo wget -q -O /etc/apt/keyrings/acton.asc https://apt.acton-lang.io/acton.gpg
sudo chmod a+r /etc/apt/keyrings/acton.asc
echo "deb [signed-by=/etc/apt/keyrings/acton.asc arch=amd64] http://apt.acton-lang.io/ stable main" | sudo tee -a /etc/apt/sources.list.d/acton.list
```
