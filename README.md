# Installation

```
git clone https://github.com/ErwanDouaille/gse-shader.git ~/.local/share/gnome-shell/extensions/
```
Change metadata version, depending of you current gnome-shell version:
```
[douaille@strela ~]$ cat ~/.local/share/gnome-shell/extensions/douailleerwan@gmail.com/metadata.json | grep version
  "shell-version": ["46.2"], 
[douaille@strela ~]$ gnome-shell --version
GNOME Shell 46.2
```
Restart gnome-shell : "alt+f2" then type "r" and validate. 

You need to install and use `gnome-tweaks` to turn on the extension. Once it's turned on, you can choose the shader you want to apply and use the slider to change some values.
If you want to add or modify any shader, place it in the extension directory with the ".frag" file extension. Gnome-shell need to be restarted to make it available in the extension menu.

