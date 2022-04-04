## Nginx SSL/TLS

[This is a part of the Nginx guide](/nginx.md)

After setting up Nginx, you may want to setup SSL through Nginx via Cerbot. To get Certbot, run the following command:
```sh
$ sudo apt install certbot
```
After installing Certbot run the following command to add SSL to your site:
```sh
$ certbot --nginx -d your.domain.com
```
Don't forget to replace `your.domain.com` with your actual domain.
