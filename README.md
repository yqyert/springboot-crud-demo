# Spring Boot CRUD Demo

Spring Boot + MyBatis 入门练习项目，实现简单的用户 CRUD 接口。

## 功能

- 用户列表查询（分页）
- 用户新增 / 编辑 / 删除
- 根据用户名模糊搜索

## 技术栈

- Spring Boot 2.x
- MyBatis
- MySQL
- RESTful API
- Postman 接口测试

## 运行

```bash
# 配置 MySQL 数据库
create database demo;

# 修改 application.yml 中的数据库连接信息
# 启动
mvn spring-boot:run
```

## 接口示例

```
GET    /api/users          # 用户列表（分页）
POST   /api/users          # 新增用户
PUT    /api/users/{id}     # 编辑用户
DELETE /api/users/{id}     # 删除用户
GET    /api/users/search?name=xxx  # 模糊搜索
```

## 说明

课程练习项目，用于熟悉 Spring Boot + MyBatis 的基本开发流程。
