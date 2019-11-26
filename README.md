本项目提供的两个配置文件，分别是用于下面的NGINX-FACADE和NGINX-FRONTEND的配置文件。

使用的时候，分别复制到nginx/conf/nginx.conf。

NGINX-FACADE （localhost:18012）  -- /ui  ---->  NGINX-FRONTEND (localhost:18010)
                                 -- /api ---->  SPRING BOOT SERVICE (localhost:18080)

