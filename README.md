# LinuxInstall
Required Packages

## apt
```shell
sudo apt install aptitude asciiart baobab bleachbit cmatrix cowsay fortune gedit htop lolcat mpv neofetch nyancat sl tlp vim g++ gcc git build-essential nvidia-driver-455 jupyter-notebook python3 python3-pip
```

## Powerline
```shell
if [ -f /usr/share/powerline/bindings/bash/powerline.sh ]; then
source /usr/share/powerline/bindings/bash/powerline.sh
fi
```

## MKCDIR
```shell
mkcdir ()
{
    mkdir -p -- "$1" &&
    cd -P -- "$1"
}
```