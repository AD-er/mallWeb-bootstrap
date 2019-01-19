## 项目简介
一个基于Laravel + Bootstrap商城前后端Demo。前端使用响应式布局，CDN资源加速，图片懒加载等主流技术，测试数据利用爬虫获取。考虑到系统安全，暂不公开后端源码。并为以下项目提供API接口：
> * 基于Laravel + Wepy微信小程序商城Demo[[GitHub源码](https://github.com/AD-er/mallWechat-wepy)]
> * 基于Laravel + React前后端完全分离的商城后台Demo[[GitHub源码](https://github.com/AD-er/mallAdmin-react)]

### 前端插件
| 插件 | 一句话描述 | 使用场景 |
| ---- | ---------- | -------- |
| [bootstrap](https://github.com/twbs/bootstrap) | 最受欢迎的 HTML、CSS 和 JS 框架 | 用于响应式布局 |
| [font-awesome](https://github.com/FortAwesome/Font-Awesome) | 一套绝佳的图标字体库和CSS框架 | 页面矢量图标 |
| [sweetalert2](https://github.com/sweetalert2/sweetalert2) | 一个漂亮的、响应式的、可定制的 JavaScript 弹窗 | 页面交互弹窗 |
| [underscore](https://github.com/jashkenas/underscore) | 一个JavaScript实用库 | 创建页面模板 |

### 后端依赖
| 扩展包 | 一句话描述 | 使用场景 |
| ------ | ---------- | -------- |
| [laravel/framework](https://github.com/laravel/laravel) | 为 WEB 艺术家创造的 PHP 框架 | 后端框架 |
| [intervention/image](https://github.com/Intervention/image) | 图片处理功能库 | 图片处理 |
| [guzzlehttp/guzzle](https://github.com/guzzle/guzzle) | 一个PHP HTTP 请求套件 | 数据请求 |
| [tymon/jwt-auth](https://github.com/tymondesigns/jwt-auth) | 用于Laravel & Lumen的JSON Web令牌认证 | API 认证 |
| [laravelsms/sms](https://github.com/phper2013/laravel-sms) | 基于 laravel 5.3+ 开发的轻量化手机短信服务包 | 手机验证 |
| [mews/captcha](https://github.com/mewebstudio/captcha) | 简单的Laravel 5服务提供商 | 验证码 |
| [predis/predis](https://github.com/nrk/predis) | Redis 官方首推的 PHP 客户端开发包 | 数据缓存 |
| [dingo/api](https://github.com/dingo/api) | 一个针对Laravel和Lumen框架的RESTful API包 | API 开发 |

### 项目安装
1). 克隆本项目源代码到本地：

     git clone https://github.com/AD-er/mallWeb-bootstrap.git

2). 切换至项目目录

     cd mallWeb-bootstrap

3). 安装扩展包依赖

     composer install

4). 生成配置文件

     cp .env.example .env

5). 生成秘钥

     php artisan key:generate

### 截图预览
以下简单截图，预览商城大体结构布局：
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-10-13_23.56.44.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-10-13_23.56.57.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-10-13_23.58.29.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-09-30_23.39.21.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-09-30_23.40.48.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-10-14_00.00.16.png?raw=true)
![预览图](https://github.com/AD-er/mallWeb-bootstrap/blob/master/preview/2018-10-14_00.02.21.png?raw=true)

### 最后
本项目[作者](https://github.com/AD-er)本人利用业余时间，断断续续设计编码。结合已掌握和新知识，参考部份开源项目。部份功能尚未完善，做得不好，当做参考。欢迎指正~
