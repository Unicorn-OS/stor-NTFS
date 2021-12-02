# TRIM  Ntfs
Useful for shrinking Backup image sizes! run before imaging.

https://askubuntu.com/questions/435825/can-ubuntu-trim-another-ntfs-partition


## Remove Hyberfile
```
device=/dev/nvme0n1p3

sudo ntfsfix $device
```

## Wipe
```
sudo ntfswipe -a -f $device
```
