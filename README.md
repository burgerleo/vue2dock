# 原指令方法
```sh
sudo docker run --name portal-rbac -v /var/www/html/frontends/portal_rbac/html:/usr/share/nginx/html -v /var/www/html/frontends/portal_rbac/conf:/etc/nginx/conf.d/ -p 8000:80 --restart=always -d nginx
```