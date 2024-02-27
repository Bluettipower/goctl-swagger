# goctl-swagger

### 1. 编译goctl-swagger插件

```
go install .
```

### 2. 配置环境

将$GOPATH/bin中的goctl-swagger添加到环境变量

### 3. 使用姿势
* 生成api/[main].api 到doc/swagger.json 文件

    ```shell script
    goctl api plugin -plugin goctl-swagger="swagger -filename doc/swagger.json" -api ./api/[main].api
    ```

