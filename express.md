### express
1. 创建服务器 `const app = express()`
2. 监听端口 `app.listen(1901,()=>{//返回结果})`
3. 静态资源服务 `app.use(['path',]express.static())`
	1. 路径不写,如何请求都能进入
	2. 路径有,根据路径进入
4. 路由(数据接口)
	1. `app.use(express.static())`
	2. `app.use(routers)`
### 中间件 `function(req,res,next){}`
1. 使用中间: `app.use([path],..ext)`
### restful api
1. get    /goods     --> 获取所有商品信息
2. post   /goods     --> 添加商品
3. get    /goods/:id --> 获取某个商品信息
4. put    /goods/:id --> 修改某个商品信息
5. 