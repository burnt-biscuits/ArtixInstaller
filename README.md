# Artix Linux Install Script
## Usage
```
git clone https://github.com/burnt-biscuits/ArtixInstaller
cd ArtixInstaller
sudo bash ArtixInstaller.sh

```
The script will ask you
- root password
- username
- user password
- hostname
- disk to install
- boot partition size
- root partition size
- enable zram or not
- filesystem to use (btrfs or ext4)
- encrypt root partition or not
- init system to use (dinit or openrc or runit or s6)
- enable archlinux repo support or not

Then, the script will do all the necessary things.

## NOTE
> This script is for clean installation only as it will wipe out the chosen disk completely.
