# installing-nodejs-in-kali-linux
Getting node.js to work in Kali Linux

# 1) install node version manager :

wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.4/install.sh | bash
  or
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.4/install.sh | zsh

depending which shell you are using: bash, zsh, fish etc. use diffrent pipe option  

# 2) close and reopen your terminal window and check if nvm get installed properly with this comand

command -v nvm

# 3) install node.js using nvm ( here we using version node.js version 6 but you can use any version you wish ):

nvm install 6
Thats it enjoy your coding ! ;)
