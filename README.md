# f32-backgrounds
A set of default and supplemental wallpapers for Fedora 32

## Testing

One way to test these is to install them on your system
* obtain the src rpm, for example using
```bash
<<<<<<< HEAD
    wget https://github.com/fedoradesign/backgrounds/releases/download/v32.2.2/f31-backgrounds-32.2.2-1.fc32.src.rpm
=======
    wget https://github.com/fedoradesign/backgrounds/releases/download/v32.2.0/f31-backgrounds-32.2.0-1.fc32.src.rpm
>>>>>>> 159f87289e88c7420d2bac1eada047908ce14e72
```
* install tools to build an rpm file, follow the guide [here](https://fedoramagazine.org/how-rpm-packages-are-made-the-source-rpm/):
```bash
    sudo dnf install fedora-packager
```    
* then build the rpm
```bash
<<<<<<< HEAD
    sudo dnf builddep f31-backgrounds-32.2.2-1.fc32.src.rpm
    rpmbuild --rebuild f31-backgrounds-32.2.2-1.fc32.src.rpm
=======
    sudo dnf builddep f31-backgrounds-32.2.0-1.fc32.src.rpm
    rpmbuild --rebuild f31-backgrounds-32.2.0-1.fc32.src.rpm
>>>>>>> 159f87289e88c7420d2bac1eada047908ce14e72
```
* to install the rpm go to the directory where it has been built, assuming the commands above have been used, the following should work
```bash
    cd rpmbuild/RPMS/noarch
```
* then install the base
```bash    
<<<<<<< HEAD
    dnf install f31-backgrounds-base-32.2.2-1.fc32.noarch.rpm
```
* finally install backgrounds for your desktop, for example for KDE 
```bash
    dnf install f31-backgrounds-kde-32.2.2-1.fc32.noarch.rpm
=======
    dnf install f31-backgrounds-base-32.2.0-1.fc32.noarch.rpm
```
* finally install backgrounds for your desktop, for example for KDE 
```bash
    dnf install f31-backgrounds-kde-32.2.0-1.fc32.noarch.rpm
>>>>>>> 159f87289e88c7420d2bac1eada047908ce14e72
```

The directory should also contain the following rpms

<<<<<<< HEAD
   * f31-backgrounds-32.2.2-1.fc32.noarch.rpm              
   * f31-backgrounds-extras-gnome-32.2.2-1.fc32.noarch.rpm  
   * f31-backgrounds-gnome-32.2.2-1.fc32.noarch.rpm
   * f31-backgrounds-animated-32.2.2-1.fc32.noarch.rpm     
   * f31-backgrounds-extras-kde-32.2.2-1.fc32.noarch.rpm    
   * f31-backgrounds-kde-32.2.2-1.fc32.noarch.rpm
   * f31-backgrounds-base-32.2.2-1.fc32.noarch.rpm         
   * f31-backgrounds-extras-mate-32.2.2-1.fc32.noarch.rpm   
   * f31-backgrounds-mate-32.2.2-1.fc32.noarch.rpm
   * f31-backgrounds-extras-base-32.2.2-1.fc32.noarch.rpm  
   * f31-backgrounds-extras-xfce-32.2.2-1.fc32.noarch.rpm   
   * f31-backgrounds-xfce-32.2.2-1.fc32.noarch.rpm
=======
   * f31-backgrounds-32.2.0-1.fc32.noarch.rpm              
   * f31-backgrounds-extras-gnome-32.2.0-1.fc32.noarch.rpm  
   * f31-backgrounds-gnome-32.2.0-1.fc32.noarch.rpm
   * f31-backgrounds-animated-32.2.0-1.fc32.noarch.rpm     
   * f31-backgrounds-extras-kde-32.2.0-1.fc32.noarch.rpm    
   * f31-backgrounds-kde-32.2.0-1.fc32.noarch.rpm
   * f31-backgrounds-base-32.2.0-1.fc32.noarch.rpm         
   * f31-backgrounds-extras-mate-32.2.0-1.fc32.noarch.rpm   
   * f31-backgrounds-mate-32.2.0-1.fc32.noarch.rpm
   * f31-backgrounds-extras-base-32.2.0-1.fc32.noarch.rpm  
   * f31-backgrounds-extras-xfce-32.2.0-1.fc32.noarch.rpm   
   * f31-backgrounds-xfce-32.2.0-1.fc32.noarch.rpm
>>>>>>> 159f87289e88c7420d2bac1eada047908ce14e72

* You can then change the wallpaper, for example on KDE, right click on the desktop and a menu should appear. Click on the menu and choose *Configure Desktop* then select the icon *Wallpaper* and choose one of the newly installed wallpers.
   
