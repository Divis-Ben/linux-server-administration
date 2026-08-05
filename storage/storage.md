# Storage Management

## Display disk usage

```bash
df -h
```

## Display directory size

```bash
du -sh .
```

## Display size of all files and folders

```bash
du -sh *
```

## List block devices

```bash
lsblk
```

## Display disk partitions

```bash
sudo fdisk -l
```

## Display mounted file systems

```bash
mount
```

## Mount a file system

```bash
sudo mount /dev/sdb1 /mnt
```

## Unmount a file system

```bash
sudo umount /mnt
```

## Display file system information

```bash
df -T
```

## Check disk usage of home directory

```bash
du -sh ~
```
