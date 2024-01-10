# Dotfiles and configs
My personal choices for my development environment 

you need to install:
- ohmyzsh
- urxvt
- tmux

to gather all the dotfiles from computer to this file so you can push the updates to github:
```
chmod +x ./gather.sh
./gather.sh
git add .
git commit -m "your msg"
git push -u origin main
```

to install all the dotfiles to your computer
```
git pull origin
chmod +x ./install.sh
./install.sh
```
