本项目依赖MkDocs([官网](https://www.mkdocs.org/))搭建，可以在自己的服务器上快速部署。

安装MkDocs前请先确保本地环境安装有`python3`和`pip`。

# 1、安装MkDocs
```
pip install mkdocs
```

# 2、拉取DSEG-wiki仓库
```
git clone https://github.com/szu-dseg/dseg-wiki
```
完成安装后拉取远程仓库到本地，进入项目目录中：
```
cd dseg-wiki
```

# 3、启动服务
```
mkdocs serve [--dev-addr $IP:$PORT]
```
这样就可以在浏览器通过http://IP:PORT/打开网站了。

