# Ubuntu Desktop 25.10 Install

## ISO used:
ubuntu-25.10-desktop-amd64.iso

## VM Configuration
- RAM: 4GB
- CPU: 2 cores
- Disk: 20 GB (VDI, Dynamically allocated)
- Network: Bridged

## Installation Summary
- Standard Ubuntu Desktop installation
- Automatic partitioning

## Post-Install Commands

```bash
cat /etc/*release 
sudo apt update
sudo apt upgrade -y --fix-missing
sudo apt install openssh-server
ip a
```

## Issues Encountered
- Ubuntu 25.10 displayed a graphics driver mismatch warning:
     see: [troubleshooting/ubuntu-desktop-25.10-graphics-driver-mismatch.md](troubleshooting/ubuntu-desktop-25.10-graphics-driver-mismatch.md)

     
## Evidence
See screenshot: 

- [screenshots/ubuntu-desktop-25.10/vm-configurations-ram-cpu-disk.png](screenshots/ubuntu-desktop-25.10/vm-configurations-ram-cpu-disk.png)
- [screenshots/ubuntu-desktop-25.10/installer-welcome.png](screenshots/ubuntu-desktop-25.10/installer-welcome.png)
- [screenshots/ubuntu-desktop-25.10/successful-first-login1.png](screenshots/ubuntu-desktop-25.10/successful-first-login1.png)
- [screenshots/ubuntu-desktop-25.10/successful-first-login2.png](screenshots/ubuntu-desktop-25.10/successful-first-login2.png)
- [screenshots/ubuntu-desktop-25.10/verification.png](screenshots/ubuntu-desktop-25.10/verification.png)
- [screenshots/ubuntu-desktop-25.10/post-install-commands1.png](screenshots/ubuntu-desktop-25.10/post-install-commands1.png)
- [screenshots/ubuntu-desktop-25.10/post-install-commands1.png](screenshots/ubuntu-desktop-25.10/post-install-commands2.png)
- [screenshots/ubuntu-desktop-25.10/post-install-commands1.png](screenshots/ubuntu-desktop-25.10/post-install-commands3.png)


