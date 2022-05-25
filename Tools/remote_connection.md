# Connect to Remote Terminal
## Tired of having to enter password everytime? Enter this command on your host machine.
```
ssh-copy-id XXX@XXX.XXX.XXX.XXX
```
## The remote server has been newly reflashed and cannot be accessed? Enter this command on your host machine.
```
mv ~/.ssh/known_hosts ~/.ssh/known_hosts_bak
```
# Transfer Files from Host Machine to Remote Server
## by rsync
```
rsync -auv /path/to/local/files XXX@XXX.XXX.XXX.XXX:/path/to/target/directory
```
## by scp
```
scp -r /path/to/local/files XXX@XXX.XXX.XXX.XXX:/path/to/target/directory
```