# LinuxInstall
Required Packages

## apt
```shell
sudo apt install htop neofetch vim g++ gcc git build-essential jupyter-notebook python3 python3-pip powerline psensor proxychains tor default-jre default-jdk
```

## snap
```shell
sudo snap install sublime-text --classic && sudo snap install telegram-desktop --classic
```

## pip3
```shell
pip3 install numpy pandas scipy matplotlib scikit-learn Keras tensorflow
```
## tensorflow-gpu
- https://medium.com/@redowan/no-bullshit-guide-on-installing-tensorflow-gpu-ubuntu-18-04-18-10-238924cc4a6a

## .bashrc file
### powerline
```shell
if [ -f /usr/share/powerline/bindings/bash/powerline.sh ]; then
source /usr/share/powerline/bindings/bash/powerline.sh
fi
```

### mkcdir
```shell
mkcdir ()
{
    mkdir -p -- "$1" &&
    cd -P -- "$1"
}
```
