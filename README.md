<p align="center">
  <img width="320" src="https://wpimg.wallstcn.com/ecc53a42-d79b-42e2-8852-5126b810a4c8.svg">
	 <h1 align="center">学生宿舍管理系统 🏠💻</h1>
</p>
<p align="center">
<img src = "https://img.shields.io/badge/Vue.js-35495e.svg?logo=vue.js&logoColor=4FC08D" />
<img src ="https://img.shields.io/badge/JavaScript-323330.svg?logo=javascript&logoColor=F7DF1E"/>
<img src = "https://img.shields.io/badge/Spring-6DB33F.svg?logo=spring&logoColor=white" />
<img src = "https://img.shields.io/badge/mysql-00000f.svg?logo=mysql&logoColor=white" />
</p>

## 📖 项目简介

## 🚀 项目名称

学生宿舍管理系统

## 🌟 项目背景
随着高校学生宿舍管理需求的日益复杂化，传统的手工管理方式已难以满足高效、便捷的管理需求。为了提升宿舍管理效率，确保信息的准确性和及时性，我们开发了基于Vue.js和SSM框架的学生宿舍管理系统。该系统旨在通过现代化的Web技术，为学生、宿舍管理员和系统管理员提供一个高效、便捷的管理平台。

## 🎉 主要功能

- **权限控制**：系统支持三种用户角色（学生、宿舍管理员、系统管理员），并根据用户角色动态生成路由，实现不同角色访问不同页面的功能。
- **报修管理**：学生可以在线提交宿舍维修申请，管理员可以实时查看并处理这些申请。
- **通知公告**：发布宿舍相关通知和公告，确保信息及时传达。
- **信息查看**：管理员用户可以在主页查看所有个人信息。
- **学生管理**：管理员可以对学生信息进行增删改查操作。
- **管理员管理**：系统管理员可以管理其他管理员账号。
- **费用缴纳**：学生可以查看和缴纳宿舍相关费用。

## 🧰 技术选型

- **前端**：基于 [vue-element-admin](https://panjiachen.github.io/vue-element-admin-site/zh/) 模板进行二次开发。
- **后端**：使用 SSM 框架。
- **数据库**：采用 MySQL 数据库。
- **开发工具**： 前端使用 VSCode，后端使用 IntelliJ IDEA。
- **版本控制**：使用 Git 和 GitHub。

## 📑 目录结构

```shell
Demo
├── backend/                # 后端项目目录
│   └── src/                # 源代码目录
│       ├── controller/     # 控制器模块，处理HTTP请求
│       ├── dto/            # 数据传输对象（DTO），用于封装处理结果
│       ├── entity/         # 实体类模块，映射数据库表结构
│       ├── mapper/         # MyBatis Mapper接口，用于数据库操作
│       └── service/        # 业务逻辑模块
│           └── serviceimpl/ # 业务逻辑实现类
│
├── frontend/               # 前端项目目录，具体开发参考vue-element-admin项目文档
├── README.md               # 项目说明文档
└── demo.sql                # SQL脚本文件，用于数据库初始化
```

## 🖥️ 构建指南

### 环境要求

- Node.js >= 8.9
- npm >= 3.0.0
- Java >= 23
- MySQL >= 8.0
- Tomcat >= 9.0

### 开发步骤

1. **克隆项目**

```shell
git clone https://github.com/MaBaixian/Demo-ssm.git
```

2. **前端开发**

```shell
# 进入前端项目目录
cd frontend

# 安装项目依赖
npm install

# 启动前端项目进行本地开发
npm run dev
```

3. **后端开发**

- 在 IntelliJ IDEA 中连接本地的 MySQL 数据库，并运行 demo.sql 脚本来还原数据库。
- 使用 Maven 安装后端项目所需的依赖。
- 修改本地数据库连接配置，更新数据库密码。

```Java
# backend/src/main/resources/application.properties
spring.application.name=backend
spring.datasource.url=jdbc:mysql://localhost:3306/demo
# 请将用户名和密码替换为本地数据库的实际用户名和密码
spring.datasource.username=root
spring.datasource.password=Ma020218
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
```

- 运行 Tomcat 启动后端服务。

## 📺Demo

这里放演示的 gif 图
