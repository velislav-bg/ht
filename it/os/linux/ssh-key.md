## create ssh key

```
  ssh-keygen -t rsa -C 'code@server.com'
```

this makes a ssh key with an identifier code@server.com

by default key files are located in home folder under .ssh subfolder

```
   ls -al ~/.ssh
``` 

id_rsa         - private key - keep it in save
id_rsa.pub     - public key - upload to servers

while creating the key you are prompted weather use passphrase when using the key in the future, if you do not want to use this extra secutiry - leave passphrase empty

## move ssh key

## use several ssh keys
