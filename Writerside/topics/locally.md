# 本地构建

- 选择导出为 `Web Archive`

<img src="local-0.png"  thumbnail="false" width="600" alt="install-0"/>

- 为页面添加服务代理

1. 将缓存文件移nginx服务器内
2. 配置代理

```nginx
    server {
            listen 7070;
            server_name localhost;
            location / {
              root /home/deploy/metads/nginx1.20.2/doc/nmc;
              index index.html;
            }
    }
```
3. 启动nginx

