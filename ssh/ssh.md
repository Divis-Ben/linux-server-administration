# SSH (Secure Shell)

## Check SSH version

```bash
ssh -V
```

## Connect to a remote server

```bash
ssh username@server-ip
```

## Generate an SSH key pair

```bash
ssh-keygen -t ed25519 -C "your-email@example.com"
```

## Copy the public key

```bash
cat ~/.ssh/id_ed25519.pub
```

## Test GitHub SSH authentication

```bash
ssh -T git@github.com
```

## Copy a file to a remote server

```bash
scp file.txt username@server-ip:/home/username/
```

## Copy a file from a remote server

```bash
scp username@server-ip:/home/username/file.txt .
```

## Securely copy a directory

```bash
scp -r project/ username@server-ip:/home/username/
```

## View known hosts

```bash
cat ~/.ssh/known_hosts
```

## View SSH configuration

```bash
cat ~/.ssh/config
```
