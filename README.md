### 项目介绍

mooding-boot 是一个轻量级的，前后端分离的J2EE快速开发平台，致力于做更简洁的快速开发平台。

每次做项目都要去找很久适合自己的项目，有时候找到的项目技术相对比较滞后，有时候前端后和后端项目不是同时让自己满意，因此利用休息日自己撸了一个比较简洁的项目，供自己和想自己的小伙伴参考使用。

该项目前端采用时比较新颖的vue3.x和element plus去做的，至少最近三年vue3.x是使用比较多的前端框架，项目实现的功能比较简单，学习和理解都比较容易，方便后续实现不同项目的业务需求。

后续会基于该项目尝试开发出仓储管理、物流管理、社区管理和人事管理项目，如有感兴趣的朋友可以从下方找到我个人社交账号，与我联系，期待你的加入。

- 后端采用Spring Boot 2.X、Spring Security、Mybatis 、Mybatis-plus、Druid、Swagger-ui、quartz、Redis 和 Jwt等框架开发。
- 前端是基于 vue3.x 、 CompositionAPI 、 typescript 、 vite 、 element plus 、 vue-router-next 、 next.vuex，适配手机、平板和pc，希望减少工作量，帮助大家实现前端快速开发

### 交流学习

QQ&微信：61600334

邮箱：moodingtech@gmail.com



###  开发环境

- 后端语言： Java 8
- 前端语言：vue3.x
- IDE(JAVA)： IDEA / Eclipse安装lombok插件
- IDE(前端)： WebStorm 或者 VScode
- 依赖管理：Maven、Yarn/Npm
- 数据库：MySQL5.7
- 缓存：Redis



###  主要特性

- 使用最新技术栈，社区资源丰富。
- 支持数据字典，可方便地对一些状态进行管理
- 支持接口级别的功能权限与数据权限，可自定义操作
- 自定义权限注解与匿名接口注解，可快速对接口拦截与放行
- 对一些常用地前端组件封装：表格数据请求、数据字典等
- 前后端统一异常拦截处理，统一输出异常，避免繁琐的判断
- 支持在线用户管理与服务器性能监控，支持限制单用户登录
- 支持运维管理，可方便地对远程服务器的应用进行部署与管理
- 高效率开发，代码生成器可一键生成前后端代码（待完善...）



###  在线体验

- 登录用户名和密码：admin/123456

  演示地址：[http://49.235.52.198:8088/](http://49.235.52.198:8088/)
  文档地址：[http://49.235.52.198:8081/api/swagger-ui/](http://49.235.52.198:8081/api/swagger-ui/)



###  内置功能

1. 用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2. 部门管理：配置系统组织机构（公司、部门、小组），树结构展现支持数据权限。
3. 岗位管理：配置系统用户所属担任职务。
4. 菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5. 角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6. 字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7. 参数管理：对系统动态配置常用参数。
8. 通知公告：系统通知公告信息发布维护。
9. 操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 系统接口：根据业务代码自动生成相关的api接口文档。
14. 服务监控：监视当前系统CPU、内存、磁盘、堆栈等相关信息。
15. 缓存监控：对系统的缓存信息查询，命令统计等。
16. 连接池监视：监视当前系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。
17. 代码生成：前后端代码的生成（java、html、xml、sql）支持CRUD下载 (待完善...)。
18. 在线构建器：拖动表单元素生成相应的HTML代码(待完善...)。

