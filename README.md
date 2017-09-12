# docker-alpine-redis

### 构建
`docker build -t rd .`
### 使用
`docker run --name redis -v e:/data:/data -d -p 6379:6379 rd`

上面的命令映射到主机的`6379`端口

### 参考
- https://docs.docker.com/samples/library/redis/
