# Some Odoo Nginx files

You will find some useful files to run Odoo with Nginx

## Getting Started

To run you Odoo with Nginx you can follow this Tutorial:

* [Odoo & Nginx](https://medium.com/@othmane.ghandi/running-odoo-in-https-using-nginx-certbot-90ef2f3e5ccb?source=friends_link&sk=2cda10893058503504401f94c0624187) - Running Odoo with Nginx

### Some changes

You need to change the file name in /etc/nginx/sites-available/your_domain.conf : You can put your real domain name

Inside /etc/nginx/sites-available/your_domain.conf:


```
port 8069 => the port that your Odoo server is using
www.your_domain.com your_domain.com => You real domain
```

