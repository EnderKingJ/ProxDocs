# Nginx
Nginx is a common tool used for load balancing as well as reverse-proxying. We will be using Nginx to pass your instance to your domains as well as to add SSL to your site.

[Installation](/nginx/install.md)

[Configuration](/nginx/configure.md)

[Securing with SSL](/nginx/ssl.md)



## SSL/TLS
After setting up Nginx, you may want to setup SSL through Nginx via Cerbot. To get Certbot, run the following command:
```sh
$ sudo apt install certbot
```
After installing Certbot run the following command to add SSL to your site:
```sh
$ certbot --nginx -d your.domain.com
```
Don't forget to replace `your.domain.com` with your actual domain.

## Authors
- [Degen-dev (Degenerate)](https://github.com/Degen-dev)
- [EnderKingJ](https://github.com/EnderKingJ)
