# libreoffice

# ATUALIZANDO O LIBREOFFICE PELO TERMINAL

Entre como root digitando su e a senha. Em seguida, digite 

sudo apt-get update e sudo apt-get upgrade

Para atualizar o sistema. Depois digite 

sudo apt-get install libreoffice*

para baixar pacotes de idiomas e outras dependências.

Em seguida, vamos instalar uma PPA (Personal Package Archives) para deixar o LibreOffice sempre atualizado, para isso digite 

sudo apt-add-repository ppa:libreoffice/ppa. 

Depois digite, quando terminal a instalação do PPA, digite 

sudo apt-get dist-upgrade

Quando terminal, reinicie a máquina e terás o aplicativo atualizado.

From the Nautilus file manager, right-click in the directory and choose the command "Open in terminal". In the terminal window you just opened, execute the command to install the language pack (with all of the commands below, you may be prompted to enter your root user's password):

For Debian/Ubuntu-based systems: sudo dpkg -i *.deb

For Fedora-based systems: su -c 'dnf install *.rpm'

For Mandriva-based systems: sudo urpmi *.rpm

For other RPM-using systems (openSUSE, etc.): rpm -Uvh *.rpm

