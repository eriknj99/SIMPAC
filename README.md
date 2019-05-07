# SIMPAC (DEPRECATED*)

*Simpac uses “--noconfirm” which is not recommended for normal installations (Use at your own risk).


Simpac is a simple tool to make installing packages easier on Arch Linux.

Simpac allows you to automatically install packages from official repositories and user repositories without the hassle of typing multiple long commands. 

# Usage 

To install a package type “simpac package-name” Simpac will first attempt to install the package using pacman from official repositories. If the package is not found in the official repos it will use yay to install it from the AUR.   

To update both pacman and yay packages type simpac --update


# Install 


`#mv simpac /bin/`
<br>
`#chmod 777 /bin/simpac`
