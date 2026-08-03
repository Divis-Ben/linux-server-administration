# File Permissions

## View file permissions

```bash
ls -l
```

## Change file permissions

```bash
chmod 755 script.sh
```

```bash
chmod 644 file.txt
```

```bash
chmod +x script.sh
```

## Change file owner

```bash
sudo chown username file.txt
```

## Change file group

```bash
sudo chgrp developers file.txt
```

## Default file permissions

```bash
umask
```

## Numeric Permission Values

| Number | Permission |
|---------|------------|
| 7 | rwx |
| 6 | rw- |
| 5 | r-x |
| 4 | r-- |
| 3 | -wx |
| 2 | -w- |
| 1 | --x |
| 0 | --- |
