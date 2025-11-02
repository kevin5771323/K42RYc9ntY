# 校园外卖平台设计与实现

## 前言

随着互联网技术的快速发展，校园外卖服务已经成为了大学生日常生活中不可或缺的一部分。本项目旨在设计并实现一个校园外卖平台，为广大师生提供便捷、高效、安全的点餐体验。

## 内容介绍

本校园外卖平台主要包括以下功能模块：用户模块、商家模块、骑手模块、订单模块、支付模块等。用户可以通过微信小程序快速浏览附近商家，下单购买美食；商家可以实时接收订单，高效管理店铺；骑手可以抢单配送，提高配送效率。此外，我们还提供了丰富的营销活动和优惠券策略，助力商家吸引更多用户。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、Mybatis、微信小程序
- 前端技术：JS、Vue、CSS3、Uniapp
- 开发工具：IDEA/Eclipse、Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为校园外卖平台的部分核心代码，展示用户模块的登录功能：

```java
@RestController
@RequestMapping("/user")
public class UserController {

    @Autowired
    private UserService userService;

    @PostMapping("/login")
    public ResponseResult<User> login(@RequestBody User user) {
        return userService.login(user.getUsername(), user.getPassword());
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/339535/29/10112/83721/68c4d976F0b2c7b39/3a0080526b42d713.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330657/17/12740/19225/68c4d94eFfb87fc20/73199878e844eb11.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329000/36/19305/20384/68c4d94eF79e54c05/4720d56339baacd4.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/346832/32/2795/40767/68c4d94eFcd89da40/1ceff577c4e30dd8.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324724/17/19362/14538/68c4d94fF6eaf7e84/939aa1ce28c12bae.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340032/8/10131/14214/68c4d94fF51b959f1/c99600b495a0b645.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/334445/33/12577/14220/68c4d94fF46a8b90e/41b9de626b88f5c7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/343384/29/2780/45517/68c4d94fF2897a5e5/fcf9081627beb954.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326081/1/19286/63047/68c4d950F2484ee2a/71eb3dd1a0e5a1e7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/327097/13/19614/10879/68c4d950Fce8b5d39/2a500b69d7c49fdd.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
