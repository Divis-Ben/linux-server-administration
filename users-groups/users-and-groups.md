USER AND GROUP MANAGEMENT

Create a new user
sudo adduser john

Delete a user 
sudo deluser john

Create a new group
sudo groupadd developers

Add a user to a group
sudo usermod -aG developers john

Display the current user 
whoami

Display user ID and groups
id

list all users
cat /etc/passwd

list all groups
cat /etc/group

