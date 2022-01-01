Things to do after installing:

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
