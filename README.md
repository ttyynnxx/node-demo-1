## node.js-test
### 启动应用
` node server.js 8888`
或者
`node server 8888`  
 ### 添加路由
 1. 编辑server.js文件，添加if else
 2. 重新运行node server.js 8888
 
 ### 后台启动应用
 touch log `node server.js 8888 >log log 2>&1 &`
