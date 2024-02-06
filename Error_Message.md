1. 
```
_universe_binary-amd64_Packages.lz4 /tmp/build-temp-2915464784 /tmp/bundle-temp-4151068201 /tmp/mcfly.8dVGPiMo /tmp/nvim.lechen /var/tmp/*
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/dev': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/sys': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/var/tmp': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/etc/resolv.conf': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/etc/hosts': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/tmp': Device or resource busy
rm: cannot remove '/tmp/build-temp-2915464784/rootfs/proc': Device or resource busy
FATAL:   While performing build: while running engine: exit status 1
```

2. Build neovim
```
100 10.6M  100 10.6M    0     0  7274k      0  0:00:01  0:00:01 --:--:-- 10.7M
+ chmod u+x nvim.appimage
+ ./nvim.appimage
dlopen(): error loading libfuse.so.2

AppImages require FUSE to run.
You might still be able to extract the contents of this AppImage
if you run it with the --appimage-extract option.
See https://github.com/AppImage/AppImageKit/wiki/FUSE
for more information
FATAL:   While performing build: while running engine: exit status 1
```

3. pip install python3-neovim error
```


ERROR: Could not find a version that satisfies the requirement python3-neovim (from versions: none)
ERROR: No matching distribution found for python3-neovim
FATAL:   While performing build: while running engine: exit status 1

```
