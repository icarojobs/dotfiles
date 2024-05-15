# dotfiles
My personal dotfiles

## INSTALLING GNU STOW AND TREE
```bash
sudo apt update
sudo apt install tree stow -y
```

## SOME COMMANDS TO HELP
```bash
# show the current directory tree
tree
```


## USAGE
In this example, I will show how to link `~/.zshrc` file to `stow` (keep the relative path structure):
```bash
cd ~/.dotfiles
cp ~/.zshrc .

# backup old file
mv ~/.zshrc ~/.zshrc.bak

# applying stow symlinks
stow .
```