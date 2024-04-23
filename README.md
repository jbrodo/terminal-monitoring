# terminal-monitoring
I want to collect and show here an (in)complete list of tools for monitoring machine resources from terminal (bash).

## Aggregated: CPU, Memory, Disks, Processes, Bandwith

### bashtop
#### On Mac
```bash
brew install bashtop
```
### On Debian/Ubuntu
```bash
sudo apt install bashtop
```

### btop
#### On Mac
```bash
brew install btop
```
### On Debian/Ubuntu
```bash
sudo apt install btop
```
### glance
#### On Mac
```
brew install glance
```
### On Debian/Ubuntu (glances not glance as for Mac)
```bash
sudo apt install glances
```
## CPU

### ps
Installed by default

### top
Installed by default

### htop
#### On Mac
```bash
brew install htop
```
### On Debian/Ubuntu
```bash
sudo apt install htop
```
## Networking, bandwith

### iftop
#### On Mac
```bash
brew install iftop
```
### On Debian/Ubuntu
```bash
sudo apt install iftop
```
### nethogs
#### On Mac
```bash
brew install nethogs
```
### On Debian/Ubuntu
```bash
sudo apt install nethogs
```

### iptraf
#### On Mac
Today, is not available on brew a version for Mac
### On Debian/Ubuntu
```bash
sudo apt install iptraf
```

## Disk write/read/IO
```bash
sudo vmstat -d
```
