
# create php.conf
```bash
sudo nano /etc/httpd/conf.d/php.conf
```

# add owener to /var/www
```bash
sudo chown -R apache:apache /var/www
```

# add read write person
```bash
sudo chmod -R 755 /var/www
```

