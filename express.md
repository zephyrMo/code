### express
1. 创建服务器 `const app = express()`
2. 监听端口 `app.listen(1901,()=>{//返回结果})`
3. 静态资源服务 `app.use(['path',]express.static())`
	1. 路径不写,如何请求
### 中间件 `function(req,res,next){}`
