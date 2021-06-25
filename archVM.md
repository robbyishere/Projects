# Arch VM

This VM has a minimal Arch Linux install with a GPU passed through for Ethereum mining


Packages installed:

`nvidia`
`xinit`
`xterm`

Steps to run VM:
1. Run this command to enable networking in virt-manager `sudo virsh net-start default` and start VM
2. Open first SSH session and run `xinit`
3. Open second SSH session and run `nvidia-smi -pl 70` and `nvidia-settings -c :0 -a "[gpu:0]/GPUMemoryTransferRateOffset[2]=1600"`
4. Close first session and run Ethereum Miner on second session


Recreating VM:


When setting up SSH, enable X11 Forwarding


