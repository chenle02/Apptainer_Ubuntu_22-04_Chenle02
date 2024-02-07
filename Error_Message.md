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
4. Nodejs latest version
```

node-tap-mocha-reporter node-tap-parser node-tar node-which node-ws nodejs-doc npm
The following packages will be upgraded:
  nodejs
1 upgraded, 0 newly installed, 23 to remove and 0 not upgraded.
Need to get 32.5 MB of archives.
After this operation, 180 MB of additional disk space will be used.
Get:1 https://deb.nodesource.com/node_21.x nodistro/main amd64 nodejs amd64 21.6.1-1nodesource1 [32.5 MB]
Fetched 32.5 MB in 3s (10.2 MB/s)
debconf: delaying package configuration, since apt-utils is not installed
(Reading database ... 50078 files and directories currently installed.)
Removing npm (8.5.1~ds-1) ...
Removing node-cacache (15.0.5+~cs13.9.21-3) ...
Removing node-move-concurrently (1.0.1-4) ...
Removing node-copy-concurrently (1.0.5-8) ...
Removing node-coveralls (3.1.1-1) ...
Removing node-tap (12.0.1+ds-4) ...
Removing node-tap-mocha-reporter (3.0.7+ds-2) ...
Removing node-tap-parser (7.0.0+ds1-6) ...
Removing node-js-yaml (4.1.0+dfsg+~4.0.5-6) ...
Removing node-esprima (4.0.1+ds+~4.0.3-2) ...
Removing node-fetch (2.6.7+~2.5.12-1) ...
Removing node-jsdom (19.0.0+~cs90.11.27-1) ...
Removing node-form-data (3.0.1-1) ...
Removing node-gyp (8.4.1-1) ...
Removing node-mime-types (2.1.33-1) ...
Removing node-mime (3.0.0+dfsg+~cs3.96.1-1) ...
Removing node-tar (6.1.11+ds1+~cs6.0.6-1) ...
Removing node-mkdirp (1.0.4+~1.0.2-1) ...
Removing node-nopt (5.0.0-2) ...
Removing node-opener (1.5.2+~1.4.0-1) ...
Removing node-which (2.0.2+~cs1.3.2-2) ...
Removing node-ws (8.5.0+~cs13.3.3-2) ...
Removing nodejs-doc (12.22.9~dfsg-1ubuntu3.3) ...
(Reading database ... 47840 files and directories currently installed.)
Preparing to unpack .../nodejs_21.6.1-1nodesource1_amd64.deb ...
Unpacking nodejs (21.6.1-1nodesource1) over (12.22.9~dfsg-1ubuntu3.3) ...
dpkg: error processing archive /var/cache/apt/archives/nodejs_21.6.1-1nodesource1_amd64.deb (--unpack):
 trying to overwrite '/usr/include/node/common.gypi', which is also in package libnode-dev 12.22.9~dfsg-1ubuntu3.3
dpkg-deb: error: paste subprocess was killed by signal (Broken pipe)
Errors were encountered while processing:
 /var/cache/apt/archives/nodejs_21.6.1-1nodesource1_amd64.deb
E: Sub-process /usr/bin/dpkg returned an error code (1)
FATAL:   While performing build: while running engine: exit status 100


```
