## Terminal Aliases

### How to use?
You can copy want alias and use this on terminal.
or You can clone this repo but don't forget global variable and features on your ```xrc``` file.
You can edit ```xrc``` file for npm or yarn. Keep the part you will use, delete the other part.


You can have a ```xrc``` file and cloned file be append like this.

```bash
-> cat thisrc >> urc
```


if you are using oh-my-zsh.

```bash
# with vim
-> vi ~/.zshrc
# with gedit or etc
-> gedit ~/.zshrc

# and use "source" command
-> source ~/.zshrc
```

if you are using default bash. Use ```~/.bashrc``` instead of ```~/.zshrc```

```bash

# Terminal Aliases by Lynicis
# General
alias godmode="sudo su"
alias offG="exit"
alias saupd="sudo apt update"
alias saupg="sudo apt upgrade"
alias sain="sudo apt install"
alias rf="sudo rm -r"

# Project
# for yarn
alias babe="yarn add"
alias babeD="yarn add -D"
alias upBabe="yarn run start"
alias buildBabe="yarn run build"
alias devBabe="yarn run dev"

# for npm
alias babe="npm i"
alias babeD="npm i -d"
alias upBabe="npm run start"
alias buildBabe="npm run build"
alias devBabe="npm run dev"
```

### Why is there no ```l``` or etc?
Because default come this on Ubuntu. But you can add like up there.
