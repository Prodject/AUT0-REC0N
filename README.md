# AUTO-RECON
## Quickly Enumerate a Target in Kali Linux
<img src="https://github.com/gotr00t0day/AUT0-REC0N/blob/master/autorecon4.gif" />

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
./auto-recon.sh -h [--help]
./auto-recon.sh -t [--target] RHOST ...check up hosts in subnet then enumerate single target IP
./auto-recon.sh -a [--all] RHOST ...check up hosts in subnet then enumerate ALL UP hosts
./auto-recon.sh -H [--HTB] RHOST ...enumerate single target and skip subnet up hosts scan
./auto-recon.sh -f [--file] RHOST ...enumerate all target IP addresses in a file
```

If you notice a bug or have a feature request. Please submit an issue. Thanks! Also, gobuster is now using the version 3 syntax, if gobuster fails, upgrade to the latest version!
