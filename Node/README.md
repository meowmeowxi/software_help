### 创建node app
##### 参考教程:https://nodejs.org/en/docs/guides/nodejs-docker-webapp/
#### 一、新建package.json
![package.json](../assets/Node/package-json.png)  
#### 二、运行`npm install`
#### 三、新建server.js
![server.js](../assets/Node/server-js.png)  
#### 四、新建Dockerfile
![Dockerfile](../assets/Node/dockerfile.png)  
#### 五、新建.dockerignore
![.dockerignore](../assets/Node/dockerignore.png)  
#### 六、构建镜像
构建镜像`docker build -t node-web-2 .`  
查看镜像`docker images`  
![docker images](../assets/Node/docker-images.png)  
#### 七、运行镜像
运行镜像`docker run -p 49160:8080 -d node-web-2`  
查看container id`docker ps`  
打印输出`docker logs <container id>`  
