# Mount NTFS read-write on Linux
```
#if os=fedora
sudo mkdir -p /run/media/ntfs
sudo mount -t ntfs -o rw $device /run/media/ntfs
```
