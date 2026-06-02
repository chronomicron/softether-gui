# softether-gui

**SoftEther Manager** – A GUI to help manage the installation and connection of the SoftEther client app on Linux.

## Features

- Install SoftEther VPN Client from source with a few clicks
- Manage virtual network adapters
- Create, edit, and delete VPN connection profiles
- Connect/disconnect to SoftEther servers
- Automatically handle DHCP and routing on Linux
- Optional desktop launcher for one-click connection

## Requirements

- Linux (tested on Linux Mint / Ubuntu-based systems)
- Python 3
- Tkinter (`python3-tk` on Debian/Ubuntu)
- `sudo` privileges

## Installation

```bash
git clone https://github.com/YOUR_USERNAME/softether-gui.git
cd softether-gui
python3 -m pip install -r requirements.txt  # if you add dependencies later
```

## Running

```bash
python3 -m semanager
# or
python3 main.py
```


