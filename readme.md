### Deploy steps to Digital Ocean
## 1 Set up SSH
If you don't have generated keys use:

```ssh-keygen -t rsa -C "my@email.com"```
Make a password or not. After, get the public key with
```cat ~/.ssh/id_rsa.pub```
You can now SSH into the box with ```ssh root@ip```

## 2 Install dependencies
Install Git with ```sudo apt-get install git```

Install MySQL with ```sudo apt-get install mysql-server```

## 3 Install Node.JS
See: https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions

For stable LTS
```
curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
sudo apt-get install -y nodejs
```
