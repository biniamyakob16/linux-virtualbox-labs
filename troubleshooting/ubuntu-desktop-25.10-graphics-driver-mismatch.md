# Ubuntu 25.10 Graphics Driver Mismatch

## Problem
- Ubuntu 25.10 displayed a graphics driver mismatch warning.
- vmwgfx Error in VirtualBox

## Cause
- Ubuntu 25.10 tried to use a VMware display driver while the actual hypervisor used was VirtualBox.

## Fix
- Changing the Graphics Controller in VirtualBox Settings from VMSVGA to VBoxSVGA.
