# Tmux

#### Install tmux
On Arch Linux
```
pacman -sS tmux
sudo pacman -S tmux
```

On Ubuntu
```
apt search tmux
sudo apt install tmux
```

#### To use my config
```
gh repo clone awesomeDev12/tmux ~/.config/tmux
```

#### Clone TPM: (Tmux Plugin Manager)
```
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

#### Install all plugins
Enter a tmux session
Press prefix + I (capital i, as in Install) to fetch the plugin.


#### Reload TMUX environment so TPM is sourced:
```
# type this in terminal if tmux is already running
tmux source ~/.config/tmux/tmux.conf
```
