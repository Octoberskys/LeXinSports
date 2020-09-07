#### 乐心运动小助手

+ 基于PyQt的一个小案例。

#### 管理页面

+ 后端服务 采用的是thinkPHP
+ 数据页面 采用Vue+TypeScript+Element-Ui
+ 数据请求 采用axios 请求 thinkPHP的接口

#### 服务搭建

+ 需要环境 Apache2.4，PHP5.6，Node.js，Mysql

+ 把Sports文件夹添加站点，二级目录设置public
+ 命令行cd 到SportsVue 里面执行`npm install`
  - 在vue.config.js中配置接口地址(就是刚刚搭建的ThinkPHP的站点)
  - 在main.ts中设置axios的baseUrl
  - 运行`npm run serve`
+ 将前台页面配置在ThinkPHP中：
  + 运行`npm run build`
  + 将打包好的index.html移动到 ThinkPHP根目录下的`application/index/view/index`文件夹下
  + 再将css，img，js，ico等静态文件移动到`public/static/`下面
  + 然后把index.html中的静态资源的路径修改一下，站点就完美使用啦

#### 挂机小工具

+ 成品在`Hearts/out/main.dist/` 目录下
+ 使用前请先配置`config.ini`   `le_url `和`info_url`
+ `le_url => 域名/api/showData`
+ `info_url => 域名/api/setInfo`

#### 总结

+ 本人技术尚浅，功能很多不完善，有兴趣的朋友可以自己动手
+ 助手成品链接 `链接：https://pan.baidu.com/s/19LeKUN2JoQWbdGb-xyW7ww 
  提取码：7tr0`
+ 学习交流
