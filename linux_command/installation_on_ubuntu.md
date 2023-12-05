## how to install nodejs on ubuntu
```
   cd Downloads/
  ls  
  tar -xf node-v20.10.0-linux-x64.tar.xz 
  ls
  cd node-v20.10.0-linux-x64/
  ls
  cd bin/
  ./node -v
  mv node-v20.10.0-linux-x64 ~/nodejs
  cd nodejs/
  cd bin/
  ./node -v
  ls -la
  nano .bashrc 
[export PATH=$PATH:/home/mir/nodejs/bin]
cd
node -v
npm -v
```
## how to install VS code on ubuntu
```
sudo apt-get install wget gpg
wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg
sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg
sudo sh -c 'echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
rm -f packages.microsoft.gpg
```
#### Update the package cache and install the package using:
```
sudo apt install apt-transport-https
sudo apt update
sudo apt install code
```
Reference: [Install vscode on ubuntu](https://code.visualstudio.com/docs/setup/linux)
