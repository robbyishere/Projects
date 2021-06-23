# Arch VM

This VM has a minimal Arch Linux install with a GPU passed through for Ethereum mining


Packages installed:


`nvidia`


`xinit`


`xterm`


Memory Overclock command:
`nvidia-settings -a "[gpu:0]/GPUMemoryTransferRateOffset[2]=1600"`


Power Limit command:
`nvidia-smi -pl 70`

