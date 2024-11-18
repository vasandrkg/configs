# Configs
This is just a collection of usefull configs for differents utilities.

# How to generate ssh key for vasandrkg user for github.com
```
cd ~/.ssh;
ssh-keygen -t rsa -b 4096 -C "vasandrkg@github.com" -f github;
```
# How to copy public ssh key for vasandrkg user to some host
```
ssh-copy-id -i ~/.ssh/github.pub vasandrkg@some_host_goes_here;
```
