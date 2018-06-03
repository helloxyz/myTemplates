# Porject Name

sub title

简述
---

项目简介

特性
---

+ [x] 项目工程相关
  * [x] 开发环境；静态文件服务器、HTTP代理、热更新
  * [x] 生产构建：代码编译提取压缩合并混淆hash命名base64~
+ [x] vue
  * [x] 组件分级 [路由级组件、复用型组件、基础组件(N3)]

使用说明
---

+ 开发环境

```
npm run dev
```

+ 生产环境

```
npm run build
```

文件结构
---

```
.
│── app.js
│── bin
│── package.json
│── public
│   │── images
│   │── javascripts
│   └── stylesheets
│── routes
│   │── index.js
│   └── users.js
└── views
    │── error.ejs
    └── index.ejs

```

效果图
---

+ 总览

![总览](./screenshot/index.png)

+ 登录

![登录](./screenshot/login.png)

+ Table

![Table](./screenshot/table.png)

+ Form

![Form](./screenshot/form.png)