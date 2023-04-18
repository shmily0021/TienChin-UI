<p align="center">
	<img alt="logo" src="https://oscimg.oschina.net/oscnet/up-d3d0a9303e11d522a06cd263f3079027715.png">
</p>
<h1 align="center" style="margin: 30px 0 30px; font-weight: bold;">TienChin v3.8.5</h1>
<h4 align="center">基于SpringBoot+Vue3前后端分离的Java快速开发框架</h4>
<p align="center">

## 平台简介

* 用于学习和联系， 若有侵权，请联系我删除。
* 本仓库为前端技术栈 [Vue3](https://v3.cn.vuejs.org) + [Element Plus](https://element-plus.org/zh-CN) + [Vite](https://cn.vitejs.dev) 版本。
* 配套后端代码仓库地址[TienChin](https://github.com/shmily0021/TienChin)。
* 提供了前端技术栈（[Vue2](https://cn.vuejs.org/) + Element + [Vue CLI](https://cli.vuejs.org/zh)），请移步[TienChin-UI2](https://github.com/shmily0021/TienChin-UI2.git)。

## 前端运行

```bash
# 克隆项目
git clone https://github.com/shmily0021/TienChin-UI.git

# 进入项目目录
cd TienChin-UI

# 安装依赖
yarn --registry=https://registry.npmmirror.com

# 启动服务
yarn dev

# 如果没有安装yarn会报错 安装yarn方式
全局安装 : npm install yarn -g

# 构建测试环境 yarn build:stage
# 构建生产环境 yarn build:prod
# 前端访问地址 http://localhost:80
```

## 内置功能

1. 线索管理
2. 商机管理
3. 合同管理
4. 促销活动
5. 私教课程
6. 统计分析
7. 渠道管理
8. 转派管理 
9. 系统管理 
   1) 用户管理：用户是系统操作者，该功能主要完成系统用户配置。 
   2) 部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。 
   3) 岗位管理：配置系统用户所属担任职务。 
   4) 菜单管理：配置系统菜单，操作权限，按钮权限标识等。 
   5) 角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。 
   6) 字典管理：对系统中经常使用的一些较为固定的数据进行维护。 
   7) 参数管理：对系统动态配置常用参数。 
   8) 通知公告：系统通知公告信息发布维护。 
   9) 操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。 
   10) 登录日志：系统登录日志记录查询包含登录异常。 
   11) 在线用户：当前系统中活跃用户状态监控。 
   12) 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。 
   13) 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 。 
   14) 系统接口：根据业务代码自动生成相关的api接口文档。 
   15) 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。 
   16) 缓存监控：对系统的缓存信息查询，命令统计等。 
   17) 在线构建器：拖动表单元素生成相应的HTML代码。 
   18) 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。