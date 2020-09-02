# Yapi docker运行环境

## 使用说明

### 克隆项目

### 创建.env
```
cp .env.example .env
```

### 启动容器
```
docker-compose up -d
```

### 进入Yapi容器
```
docker-compose exec yapi bash
``` 

### 启动部署服务
```
yapi server
```

### 访问页面完成部署


### pm2启动服务
```
cd /my-api
pm2 start "vendors/server/app.js" --name yapi
```

