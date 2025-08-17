django是一个大而全的框架，flask是个轻量级的框架
django内部有非常多的组件，orm/session/cookie/admin/form/modelform/路由/视图/模板/中间件/分页/auth/contenttype/缓存/信号/多数据库连接

flask本身无太多功能：路由/视图/模板（jinja2）/session/中间件，第三方组件齐全
django的请求处理是逐一封装和传递；flask的请求是利用上下文管理来实现的

内容回顾：
1.什么是jwt？
2.cmdb的实现原理
3.都用到了哪些命令？
4.遇到过哪些bug？
5.什么是开封封闭原则？
# 今日概要
- flask快速使用 
- 实现管理系统
- 蓝图blue print   标准目录结构
# 今日详细
## flask快速使用 
1.1 依赖wsgi（web服务网关接口）Werkzeug
  




 1.2 模板渲染  Jinja2