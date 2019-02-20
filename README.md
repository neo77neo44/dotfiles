# dotfiles

# install power-line fonts
git clone https://github.com/powerline/fonts.git --depth=1

cd fonts

./install.sh

# clean-up a bit
cd ..

rm -rf fonts

# install ncurses 
sudo apt-get install libncurses5-dev

# install java
sudo apt install default-jdk

sudo apt install default-jre
