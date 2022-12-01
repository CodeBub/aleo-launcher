# aleo-launcher

启动步骤：
1. 安装 docker 
```
curl -s https://get.docker.com | bash -s 
```
2. 下载配置文件 
```
wget 'https://raw.githubusercontent.com/CodeBub/aleo-launcher/main/docker-compose.yaml'
```
3. 配置自己的key
编辑docker-comopose.yaml文件，将 prover 后面改成自己的 private_key
![修改key](https://github.com/CodeBub/aleo-launcher/raw/main/private_key.png)
4. 启动脚本 
```
docker compose up -d
```

完事，手工
![启动效果](https://github.com/CodeBub/aleo-launcher/raw/main/screenshot-20221201-173602.png)

