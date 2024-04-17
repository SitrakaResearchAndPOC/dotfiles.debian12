# PRE-INSTALLATION
```bash
git clone --depth 1 https://github.com/henintsoa98/dotfiles.debian12
cd dotfiles.debian12
```
## CAUTION
NEVER RUN COMMAND AS ROOT, it use sudo itself. \
$USER is generally in sudo group, but if not, run :
```bash
bash sudo.bash
```
# INSTALLATION
This command will help you to install some package, with their configuration. \
Accept recommanded if you want to get better experience, or if you are from [hyprland.debian12](https://github.com/henintsoa98/hyprland.debian12) \
Just run :
```bash
bash setup.bash
```
If you don't like all of this stuff, you can explore some script or config in BIN, CONFIG.

```
fc-cache -r
```
```
fc-cache -v
```
# Active zsh
```
chsh -s $(which zsh)
```

# For reconfigure
```
pl10k configure
```

# AFTER INSTALLATION
After installation and setting up zsh correctly, and after getting into zsh, run :
```bash
bash pl10k_patch.bash
```
# SPLIT SCREEN
[link ](https://askubuntu.com/questions/171160/how-can-i-split-the-standard-ubuntu-terminal)

* Installing terminator (for gnome and KDE)
```
apt-get install terminator
```
* Installing splitvt
```
apt-get install splitvt
```
* Installing tilix
```
apt-get install tilix
```
* Installing tilix
```
apt-get install tilix
```
* Installing tmux
```
sudo apt install tmux
```
</br>
tmux </br>
Ctrl+b " Split current pane horizontally into two panes </br>
Ctrl+b % Split current pane vertically into two panes </br>
Ctrl+b o Go to the next pane </br>
Ctrl+b ; Toggle between the current and previous pane </br>
Ctrl+b x Close the current pane </br>
Ctrl+b d keep your terminal running in background (you can close the terminal even if a socket is running. </br>
Ctrl+b w list your panes (e.g. after reopening the terminal) </br>
Ctrl+b [ Activate scroll. Use ESC to exit. </br>
For more options you can see [here](https://linuxize.com/post/getting-started-with-tmux/) </br>

# INSTALLING THEMATIC 
[link1](https://www.geeksmint.com/best-ubuntu-themes/)
[link2](https://www.omgubuntu.co.uk/2017/11/best-gtk-themes-for-ubuntu)
* flat thematic
```
sudo add-apt-repository ppa:daniruiz/flat-remix
```
```
sudo apt update
```
```
sudo apt install flat-remix-gnome
```
* paper thematic
```
sudo add-apt-repository -u ppa:snwh/ppa
```
```
sudo apt-get update
```
```
sudo apt install paper-icon-theme
```
```
if you want to install the icons and colors
```
sudo apt-get install paper-icon-theme
```
#sudo apt-get install paper-cursor-theme

# ADDING SCREEN WALL PAPER
[wallpaper](https://github.com/SitrakaResearchAndPOC/Fond)
