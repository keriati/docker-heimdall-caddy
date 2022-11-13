# Heimdall with Caddy and MariaDB

Use Heimdall with green https on your local network with MariaDB.

Requirements
 - Own domain
 - Cloudflare DNS setup for your domain
 - Cloudflare API Token with zone and dns access

Environment variables:

 - APP_DIR
 - CLOUDFLARE_EMAIL
 - CLOUDFLARE_API_TOKEN
 - HEIMDALL_DOMAIN
 - MYSQL_ROOT_PW
 - MYSQL_DB
 - MYSQL_USER
 - MYSQL_PASSWORD