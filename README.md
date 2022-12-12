# m133-njaro
Patch the Manjaro Kernel with the IOXO M133-N touchpad driver.

I recommend that you enable the "Use number pad to move cursor" option menu within Accessibility Settings to install Manjaro and download the release from GitHub.

## Installation
Download the two packages under the releases section of this GitHub repository. Install the packages with pacman.

`sudo pacman -U Downloads/linux510-5.10.66-1-x86_64.pkg`

`sudo pacman -U Downloads/linux510-headers-5.10.66-1-x86_64.pkg`

## Avoid Future Updates Overwriting this Kernel
Add the following line to `/etc/pacman.conf`

`IgnorePkg   = linux??? linux???-headers`
