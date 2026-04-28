# Kali Linux VM Setup

## Installazione
- Installazione Kali Linux in VirtualBox
- Partizionamento: Guided - use entire disk
- GRUB su /dev/sda
- Display manager: gdm3

## Post installazione
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y git curl wget net-tools
