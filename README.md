# ST_task

#### 介绍




## 安装教程
# gin-vue-admin web

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```


### Backend Server (Go)
```bash
# Navigate to server directory
cd server

# Install dependencies
go mod download

# Update Swagger documentation
swag init -g server/main.go

# Run server (development mode)
go run main.go

# Run with config file
go run main.go -c config.yaml

```


# docker启动
```bash
# 在项目根目录运行
cd backed_admin/server
docker-compose up -d