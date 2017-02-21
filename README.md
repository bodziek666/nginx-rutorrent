Simple template for nginx + php-fpm + let's encrypt + rutorrent 

Replace pathes etc. with your own. 

Put "letsencrypt.conf" and "ssl.conf" under `/etc/nginx`

Put "rutorrent" under `/etc/nginx/sites-available` and create symlink to `/etc/nginx/sites-enabled`

You can use "include ssl.conf" in "nginx.conf" or just copy and paste it to nginx.conf 

tl;dr: works on my machine :)   
