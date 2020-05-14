# Usage - Kmalloc

test kmalloc syscall:
```sh
make
sudo kldload ./module/kmalloc.ko
./interface/interface 4
```

unload kmalloc syscall:
```sh
sudo kldunload ./module/kmalloc.ko
```