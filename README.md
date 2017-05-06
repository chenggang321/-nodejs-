# -nodejs-
项目采用nodejs+express+mongodb+mongoose,搭建一个个人博客系统，在项目中我们实现了用户注册、登录、博客文章列表、内容预览和评论功能，后台的：注册用户管理、博客分类管理、博客内容以及评论的管理功能。
1、通过express搭建一个web应用程序（网站）；
2、使用mongodb保存持久化保存数据；
3、使用node模块：mongoose设计维护和操作mongodb数据库和数据，实现了对数据的结   构化存储和CURD（增、删、改、查）操作；
4、使用swig实现前后端分离
5、其他各种 express 中间件技术：
  a）static中间件实现静态资源托管；
  b）cookies中间件实现cookie的操作，完成用户登录状态、权限信息验证功能；
   c）body-parser中间件实现对post数据进行解析；
6、自定义中间件实现统一数据验证和处理；
7、功能模块分层开发；
8、ajax的api接口设计开发和应用；
使用的模块以及第三方插件如下：
基础框架：
nodejs（基础核心开发语言）、express@4.14.0（nodejs web开发框架）、mongodb（数据库）
第三方模块插件
bodyParser(解析post请求)、cookies（读/写cookies）、swig（模板解析引擎）、mongoose（操作mongodb数据）、markdown语法解析模块
