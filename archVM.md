# Arch VM

This VM has a minimal Arch Linux install with a GPU passed through for Ethereum mining


Packages installed:

`nvidia`
`xinit`
`xterm`

Steps to run VM:
1. Open first SSH session and run `nvidia-smi -pl 70` and `xinit`
2. Open second SSH session and run `nvidia-settings -c :0 -a "[gpu:0]/GPUMemoryTransferRateOffset[2]=1600"`
3. Close first session and run Ethereum Miner on second session
