git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim


The ycmd server SHUT DOWN

cd ~/.vim/bundle/YouCompleteMe

./install.py


cp -rf ~/.vim/bundle/gruvbox/colors ~/.vim/

Ubuntu

oh my zsh

sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"

Failed to connect to raw.githubusercontent.com port 443: Connection refused

DNS

sudo /etc/init.d/nscd restart

git clone https://github.com/fcamblor/oh-my-zsh-agnoster-fcamblor.git

cd oh-my-zsh-agnoster-fcamblor/

./install

ZSH_THEME="agnoster"

iTerm2

https://github.com/mbadolato/iTerm2-Color-Schemes

Powerline

pip3 install powerline-status --user

git clone https://github.com/powerline/fonts.git --depth=1

cd fonts

./install.sh

iTerm2 -> Preferences -> Profile -> Colors -> Color Presets -> Gruvbox Dark

iTerm2 -> Preferences -> Profile -> Text -> Font -> Meslo LG M for Powerline

cd ~/.oh-my-zsh/custom/plugins/

git clone https://github.com/zsh-users/zsh-autosuggestions

cd ~/.oh-my-zsh/custom/plugins/

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git

plugins=(

    git
    
    zsh-autosuggestions
    
    zsh-syntax-highlighting
    
)

source $ZSH/oh-my-zsh.sh

source $ZSH/custom/plugins/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh

MacVim

alias vim='mvim -v'

~/.tmux.conf

Ubuntu

sudo mkdir -p /usr/share/fonts/monaco

sudo mv monaco.ttf /usr/share/fonts/monaco

sudo chmod 744 /usr/share/fonts/monaco/monaco.ttf

sudo mkfontscale

sudo mkfontdir

sudo fc-cache -fv

Powerline

sudo apt-get install fonts-powerline

Ubuntu Gnome Terminal

https://github.com/metalelf0/gnome-terminal-colors

sudo apt-get install dconf-cli

git clone https://github.com/metalelf0/gnome-terminal-colors.git

cd gnome-terminal-colors

./install.sh

prevent accidental logout by hitting Ctrl+d

setopt ignoreeof

