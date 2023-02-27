## Build Setup

```bash
# 克隆项目
git clone https://github.com/blueisland-xx/myhoutai.git

# 进入项目目录
cd myhoutai

# 安装依赖
npm install

# 可以通过淘宝镜像 解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

## 文件介绍

```bash
build
     ----index.js webpack配置文件【很少修改这个文件】
mock
    ----mock数据的文件夹【模拟一些假的数据mockjs实现的】，因为实际开发的时候，用的是真实的接口

node_modules
     ------项目依赖的模块

public
     ------ico图标,静态页面，publick文件夹里面经常放置一些静态资源，而且在项目打包的时候webpack不会编译这个文件夹，原封不动的打包到dist文件夹里面

src
    -----源代码文件夹
    ------api文件夹:涉及请求相关的
    ------assets文件夹：里面放置一些静态资源（一般共享的），放在aseets文件夹里面静态资源，在webpack打包的时候，会进行编译
    ------components文件夹：一般放置非路由组件获取全局组件
    ------icons这个文件夹的里面放置了一些svg矢量图
    ------layout文件夹：他里面放置一些组件与混入
    ------router文件夹：与路由相关的
    -----store文件夹：一定是与vuex先关的
    -----style文件夹：与样式先关的
    ------utils文件夹：request.js是axios二次封装文件****
    ------views文件夹：里面放置的是路由组件

App.vue:根组件
main.js：入口文件
permission.js:与导航守卫相关
settings：项目配置项文件
.env.development
.env.producation
```

## 接口文档
- http://39.98.123.211:8170/swagger-ui.html#/
- http://39.98.123.211:8216/swagger-ui.html

## 后台路由

![image-20220609120120695](https://150-9155-1312350958.cos.ap-chengdu.myqcloud.com/img202206091350089.png)

## 技术选型

![image-20220609120147762](https://150-9155-1312350958.cos.ap-chengdu.myqcloud.com/img202206091350091.png)

## 登录业务

-----静态组件完成
-----书写 API（换成真实的接口）
-----axios 二次封装
-----换成真实接口之后需要解决代理跨域问题(解决代理跨域问题)

![image](https://github.com/blueisland-xx/image-store/blob/master/image/back1.png)

## 首页业务

![image](https://github.com/blueisland-xx/image-store/blob/master/image/index.png)

## 品牌管理组件

![image](https://github.com/blueisland-xx/image-store/blob/master/image/product.png)

## 添加品牌与修改品牌


## 删除品牌的操作

## SPU 模块介绍

SPU 你可以理解为类

People 类【SPU】
实例:【SKU】

## SPU 管理内容切换

---展示 SPU 列表结构
----添加 SPU|修改 SPU
----展示添加 SKU 结构

## SKu 的业务

SKU 的上架与下架操作

SKU 模块数据的展示

查看信息


## 权限管理

权限管理：用户管理、角色管理、菜单管理

## 菜单管理

