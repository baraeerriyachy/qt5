# dark.conf
> A dark theme compatible with gtk4 for qt5.
# requirement
- qt5ct
# Installation 
```
git clone https://github.com/baraeerriyachy/qt5
cd qt5
sudo mv dark.conf /usr/share/qt5ct/colors
```
# Activation
1. add `QT_QPA_PLATFORMTHEME=qt5ct` to `/etc/environment`
2. run `qt5ct`
3. select `Custom`
4. change color scheme to `dark`
