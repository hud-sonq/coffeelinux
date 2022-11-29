# CoffeeLinux

### For most ARM based SoC's, this is all you need to boot. 
### It is an Ubuntu Bionic server, with all network options configured for docker and k8s

# How to use

### Go ahead and mount your drive and then extract the contents of ```rootfs.tar.bz2``` onto it. Unmount it, and when you boot just select the partition with the files.

### It's as simple as:
```shell
sudo mount [dev part] [destination]
sudo tar -xvf rootfs.tar.bz2 [destination]
sudo umount [destination]
```
