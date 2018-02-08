# SIMPAC                                     

Simpac is a simple tool to make installing packages easier on Arch Linux.

Simpac allows you to automatically install packages from official repositories and user repositories without the hassle of typing multiple long commands. 

# Usage 

To install a package type “simpac package-name” Simpac will first attempt to install the package using pacman from official repositories. If the package is not found in the official repos it will use yaourt to install it from the AUR.   

To update both pacman and yaourt packages type simpac --update

To automaticaly install yaourt type simpac --install-yaourt

# Install 

Simpac is a bash script and can be manually executed using ./simpac. 
 
To make simpac executable globally add:

export PATH=$PATH:/simpac/folder/ to ~/.bashrc

This can be done with a single command using 

sudo echo $PATH:$HOME >> ~/.bashrc

(Replace $HOME with the directory that the simpac script is located)
