# Dockerize Nextcloud with multiple components

- MariaDB
- Redis
- nginx
- cron
- SSL

## Environment variables

```env
# Database
MYSQL_PASSWORD=nextcloud
MYSQL_DATABASE=nextcloud
MYSQL_USER=nextcloud
MYSQL_ROOT_PASSWORD=nextcloud

# Nextcloud
NEXTCLOUD_ADMIN_USER=admin
NEXTCLOUD_ADMIN_PASSWORD=password

# Nginx
VIRTUAL_HOST=localhost

# SSL
SSL_SUBJECT=localhost
CA_SUBJECT=my@home
SSL_KEY=/certs/localhost.key
SSL_CSR=/certs/localhopst.csr
SSL_CERT=/certs/localhost.crt
```

