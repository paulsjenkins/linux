sudo dnf install neovim exa bat vifm tig

wget -qO- https://git.io/papirus-icon-theme-install | sh

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash

sudo dnf install gnome-shell-extension-pop-shell xprop

cat << EOF | sudo tee ~/.config/gtk-3.0/gtk.css

VteTerminal,

 TerminalScreen,
 
 vte-terminal {
     padding: 15px 15px 15px 15px;
     -VteTerminal-inner-border: 10px 10px 10px 10px; 
 }
 
EOF

bash -c "$(curl -fsSL https://raw.githubusercontent.com/ohmybash/oh-my-bash/master/tools/install.sh)"
