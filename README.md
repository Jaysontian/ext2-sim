**Simulation of EXT2 filesystem in C** 🗄️

- 1024 B block size with 128 inodes
- 4 active inodes (2 dirs, 1 file, 1 slink)

Run the program with:
```shell
make
```
Then create the mountable EXT2 filesystem image with:
```shell
./ext2-create
```

Verify the validity of the filesystem with `fsck`:
```shell
fsck.ext2 cs111-base.img
```


