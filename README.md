### Dockerfile 优化实践
* 使用Alpine作为基础镜像
* 使用多阶段构建
* 使用Nginx作为静态服务器

### demo
```
// 打包
docker build -t app:v1

// 运行
ocker run -d -p 8080:80 app:1
```
