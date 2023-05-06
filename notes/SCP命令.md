#### 从远程主机复制到本地

- ``` scp -i Desktop/DEV.pem centos@13.213.10.175:/data/www/tdex_api/storage/logs/laravel.log Desktop/ ```
- 如果使用账号密码，去掉 -i 选项就行

#### 从本地复制到远程主机

- ``` scp -i Desktop/DEV.pem Desktop/laravel.log centos@13.213.10.175:/data/www/tdex_api/storage/logs/laravel.log ```