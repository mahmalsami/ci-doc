
#Apache
##Install Apache
```sh
apt-get install apache2
```


##Show Apache access errors
```sh
sudo tail -100 /var/log/apache2/access.log
```


## Load apache vhost config
sudo a2enmod vhost_alias
