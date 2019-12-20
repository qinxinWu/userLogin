# userLogin
这是前端用React、后端用Go写的用户登录的功能

#部署流程

#前端部署流程
1、安装好node.js 和 react的环境
2、安装axios和jquery的依赖包
3、进入到loginClient项目根目录下用npm start启动

#后端部署流程
1、直接把loginServer项目根目录下main文件（注意没有后缀名、不是main.go就是main文件）直接放到linux服务器上
2、执行chmod 777 main
3、执行./main 即可，后端就启动了
4、api是：http://localhost:8081/login;两个参数是username和password。

备注：由于后端写死，所以只有当username=wqx,password=123时才会登录成功前端页面会弹出弹窗显示：login ok，
     其他情况登录失败会前端页面会弹出弹窗显示：login fail
