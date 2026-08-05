# User and Group Management

## Create a new user
```bash
sudo adduser john
```

## Delete a user
```bash
sudo deluser john
```

## Create a new group
```bash
sudo groupadd developers
```

## Add a user to a group
```bash
sudo usermod -aG developers john
```

## Display the current user
```bash
whoami
```

## Display user ID and groups
```bash
id
```

## List all users
```bash
cat /etc/passwd
```

## List all groups
```bash
cat /etc/group
```

