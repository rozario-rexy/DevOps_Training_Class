# Linux User and Group Management

## Create a new user

`#sudo adduser john`

## List all user on the system
`#cat /etc/passwd`

## create a user without a home directory in Linux

`sudo adduser --no-create-home username`

## Change user details

`sudo usermod -c "New Full Name" username`

## Change the username

`sudo usermod -l new_username old_username`

## Change the user's home directory:

`sudo usermod -d /new/home/directory username`

## Grant sudo privileges to the user

`sudo usermod -aG sudo john`

## Display user information

`finger username`

## Display information about a user or group, user ID and group membership
`id username`
## Lock the user account
sudo passwd -L john
#Unlock the user account
sudo passwd -u john
#Change User Password
sudo passwd username
#Change user password
sudo passwd john
#Remove the user
sudo deluser john
#Remove user together with his/her home directory
sudo deluser --remove-home user
