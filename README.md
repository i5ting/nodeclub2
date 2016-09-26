# nodeclub2：构建更加开放的nodeclub2

- 从现有cnode上独立api测试
- 从现有cnode上独立dao（即model层操作）,发到npm上
- 用koa 2重写api
  - router
  - middleware
  - controller
  - common
- 把ep去掉，换成async/await + promise
- 前端独立，可以有多种实现，默认vue2主站前端
- 社区分发子域名,CNAME，比如i5ting.cnodejs.org可以自己实现前端
