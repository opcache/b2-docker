# b2-docker
> WordPress网站7b2主题专用docker容器环境

# 优势
> 1. 容器镜像采用基于docker容器alpine系统构建nginx+php+mariadb环境，网络采用docker host方式，日志可以获取到用户真实IP
>    地址   https://github.com/opcache/danmp
> 2. 可以支持lua waf拦截非法请求，可以自定义规则
> 3. mysql默认密码为test123123

# 安装
```
cd /opt/
wget https://github.com/opcache/b2-docker/archive/master.zip
unzip master.zip
cd b2-docker-master
bash install.sh
```

# 卸载
```
cd b2-docker-master
bash uninstall.sh
```


# 友情技术支持站点和开源工具

> <https://aqzt.com/>

> <https://selinux.cn/>

> <https://7b2.com/>

> <https://github.com/loveshell/ngx_lua_waf>

> <https://github.com/taihedeveloper/ngx_lua_waf>


