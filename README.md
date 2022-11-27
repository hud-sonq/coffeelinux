# CoffeeLinux

### For most ARM based SoC's, this is all you need to boot. 
### It is an Ubuntu Bionic server, with all network options are configured for docker and k8s

# How to use

### Go ahead and mount your drive and then extract the contents of ```rootfs.tar.bz2``` onto it. Unmount it and then just make the partition your boot selection


```shell
// with file in pwd:

sudo mount [dev part] [destination]
cd [destination]
sudo tar -xvf rootfs.tar.bz2 
sudo umount [destination]
```
