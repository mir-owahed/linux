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


## How to write 1st nodejs code 

```

mkdir nodejs-helloWorld
cd nodejs-helloWorld/
code .
npm init
  npm i express
  npm i nodemon -D
  npm start
  npm run dev
  node app.js
  npm run start
```
#### packaje.json snippet
```
{
  "name": "nodejs-helloworld",
  "version": "1.0.0",
  "description": "This is my 1st nodejs code!!!!!!!!!",
  "main": "app.js",
  "scripts": {
    "start": "node app.js",
    "dev": "nodemon app.js"
  },
  "author": "mir-owahed-ali",
  "license": "ISC",
  "dependencies": {
    "express": "^4.18.2"
  },
  "devDependencies": {
    "nodemon": "^3.0.2"
  }
}
```
Reference: [app.js](https://expressjs.com/en/starter/hello-world.html)

## How to create python virtual environment
```
cd
nano .bashrc
[alias python=python3
sudo apt install python3.10-venv
sudo apt install python3-pip
python -m venv venv
code .
source venv/bin/activate
```
## How to create fastapi

```
pip install fastapi
pip install "uvicorn[standard]"
uvicorn main:app --reload

```
Reference: [fastapi](https://fastapi.tiangolo.com/tutorial/first-steps/)



