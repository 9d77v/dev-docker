# dev-docker
基于docker的本地开发环境

# 启用服务
cp .env.example .env

修改.env中的参数
## 启用全部服务
docker-compose up -d
## 启用部分服务
docker-compose up -d mysql redis phpredisadmin
# 启用远程服务
cd ssh

cp .env.example .env

同时修改docker-compose.yml和.env

docker-compose up -d
