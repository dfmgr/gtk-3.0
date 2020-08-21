## gtk-3.0  
  
GTK, or the GIMP Toolkit, is a multi-platform toolkit for creating graphical user interfaces  
  
requires:    
```
apt install gtk-3.0
```  
```
yum install gtk-3.0
```  
```
pacman -S gtk-3.0
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/gtk-3.0/raw/master/install.sh)"
```
Manual install:
```
sudo bash -c "$(curl -LSs https://github.com/casjay-themes/linux/raw/master/install.sh)"
mv -fv "$HOME/.config/gtk-3.0" "$HOME/.config/gtk-3.0.bak"
git clone https://github.com/dfmgr/gtk-3.0 "$HOME/.config/gtk-3.0"
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/GTK" target="_blank">gtk-3.0 wiki</a>  |  
  <a href="https://www.gtk.org" target="_blank">gtk-3.0 site</a>
</p>  
