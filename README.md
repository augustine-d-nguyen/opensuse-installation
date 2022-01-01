Things to do after installing:
```
sudo zypper ref && sudo zypper up

sudo zypper remove libreoffice*

sudo zypper install git

sudo zypper install terminator

sudo zypper install zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

sudo zypper ar https://packages.microsoft.com/yumrepos/edge edge

sudo zypper addrepo https://packages.microsoft.com/yumrepos/vscode vscode

sudo rpm --import https://packages.microsoft.com/keys/microsoft.asc

sudo zypper refresh

sudo zypper install microsoft-edge-stable

sudo zypper install code

(cd ~/Downloads && curl -o jdk.rpm https://download.oracle.com/java/17/latest/jdk-17_linux-x64_bin.rpm)

sudo rpm -ivh ~/Downloads/jdk.rpm

sles_version="$(. /etc/os-release && echo "${VERSION_ID##*.}")"

opensuse_repo="https://download.opensuse.org/repositories/security:SELinux/SLE_15_SP$sles_version/security:SELinux.repo"

sudo zypper addrepo $opensuse_repo

sudo zypper remove docker docker-client docker-client-latest docker-common docker-latest docker-latest-logrotate docker-logrotate docker-engine runc

sudo zypper addrepo https://download.docker.com/linux/sles/docker-ce.repo

sudo zypper install docker-ce docker-ce-cli containerd.io

sudo systemctl start docker

sudo docker run hello-world

sudo groupadd docker

sudo usermod -aG docker $USER

newgrp docker

docker run hello-world

sudo zypper install telegram-desktop

sudo zypper install discord

```

