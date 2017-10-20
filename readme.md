# ECHO 学习Demo

## 简介

此项目主要用于学习使用传说中比其他Go web框架性能高10倍的[ECHO](https://github.com/labstack/echo)

> 项目使用 glide 构建

## 项目中使用到包

日志： github.com/donnie4w/go-logger/logger

单元测试：github.com/smartystreets/goconvey

数据库查询：github.com/jmoiron/sqlx

mysql驱动：github.com/go-sql-driver/mysql

配置文件解析：github.com/BurntSushi/toml

## 使用说明

- 执行 doc目录下的sql文件，创建数据库

- 使用glide 构建项目，如果有包无法下载请自行想办法解决

- 启动项目访问 http://localhost:8080/user.html 

  - 单元测试

    - 在service目录执行 `go test` 命令
    - 使用`goconvey`命令启动goconvey测试工具，查看测试结果。



