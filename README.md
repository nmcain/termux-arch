# termux-arch

A script to install an Arch chroot in Termux

You need to install wget and proot in Termux before using this script.

```
pkg install wget proot
```

The script will make its files in the current directory. So if you want your Arch-filesystem at a particular location switch to that folder first and then call the script with it's relative path. Example:
```
mkdir -p ~/nmcain/arch
cd ~/nmcain/arch
wget https://raw.githubusercontent.com/Neo-Oli/termux-ubuntu/master/ubuntu.sh
bash arch.sh
```

After running it you can run "start-arch.sh" to switch into your ubuntu

