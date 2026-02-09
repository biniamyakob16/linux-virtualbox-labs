# Ubuntu Server 25.10 Install

## ISO used:
ubuntu-25.10-live-server-amd64.iso

## VM Configuration
- RAM: 4GB
- CPU: 2 cores
- Disk: 20 GB (VDI, Dynamically allocated)
- Network: NAT

## Installation Summary
- Standard Ubuntu Server installation
- Automatic partitioning

## Post-Install Commands

```bash
lsb_release -a  
sudo apt update
sudo apt upgrade -y --fix-missing
sudo apt install openssh-server
ip a
```

## Issues Encountered
- Virtualbox failed to start VM due to KVM conflict:
     see: [troubleshooting/virtualbox-kvm-conflict.md](troubleshooting/virtualbox-kvm-conflict.md)
     
## Evidence
See screenshot: 
- [screenshots/ubuntu-server-25.10/vm-configurations-cpu&ram.png](screenshots/vm-configurations-cpu&ram.png)
- [screenshots/ubuntu-server-25.10/vm-configurations-disk.png](screenshots/ubuntu-server-25.10/vm-configurations-disk.png)
- [screenshots/ubuntu-server-25.10/installer-welcome.png](screenshots/ubuntu-server-25.10/installer-welcome.png)
- [screenshots/ubuntu-server-25.10/disk-configuration.png](screenshots/ubuntu-server-25.10/disk-configuration.png)
- [screenshots/ubuntu-server-25.10/successful-first-login.png](screenshots/ubuntu-server-25.10/successful-first-login.png)
- [screenshots/ubuntu-server-25.10/verification.png](screenshots/ubuntu-server-25.10/verification.png)
- [screenshots/ubuntu-server-25.10/post-install-commands.png](screenshots/ubuntu-server-25.10/post-install-commands.png)


