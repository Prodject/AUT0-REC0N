# AUTO-RECON
## Easy to use script to quickly scan a Target in Kali Linux

![alt text](https://github.com/gotr00t0day/AUT0-REC0N/blob/master/Auto-Recon-3-0.PNG)

### INSTALLATION
```
cd /opt
git clone https://github.com/Knowledge-Wisdom-Understanding/Auto-Recon.git
cd Auto-Recon
chmod +x setup.sh
./setup.sh
```

### Usage:
```
./auto-recon.sh RHOST
```
### Terminal Geometry
The gnome-terminal geometry is configured for 2 screens. If the new terminal windows don't open up the way that you like,
position a terminal window to where you want it and run this command to get the geometry coordinates.
```
xwininfo -id $(xprop -root | awk '/_NET_ACTIVE_WINDOW\(WINDOW\)/{print $NF}')
```
The -geometry will be at the bottom. Then proceed to edit auto-recon.sh as needed. Currently new terminal windows open up at a zoom-level 
of 0.9
If you notice a bug or have a feature request. Please submit an issue. Thanks!
