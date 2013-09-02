## Setup

1. Clone this repo
2. Create symlinks:

### Windows

```
cd "C:\Users\martins.sipenko\AppData\Roaming\Sublime Text 3"
mklink /D "Installed Packages" "C:\Users\<username>\Dropbox\appdata\sublime3\Installed Packages"
mklink /D "Packages" C:\Users\<username>\Dropbox\appdata\sublime3\Packages" 
```

### Unix
```
cd ~/.config/sublime-text-3/
rm -rf Packages/
rm -rf Installed\ Packages/

ln -s ~/Dropbox/sublime-text-3/Packages/
ln -s ~/Dropbox/sublime-text-3/Installed\ Packages/
```
