## 前言

随着新冠疫情的全球爆发，人们的生活方式发生了很大改变，尤其对于小区居民的日常生活购物造成了诸多不便。基于此，我们开发了一套基于Springboot的小区疫情购物系统，旨在为广大小区居民提供一个安全、便捷的在线购物平台。以下是该项目的详细介绍。

## 内容介绍

本项目是一款基于Springboot的小区疫情购物系统，主要功能包括：用户注册登录、商品浏览、购物车、订单管理、疫情信息查询等。通过使用Java语言和Spring Boot框架，结合前端技术Vue、JS和CSS3，为用户提供了一个易用、高效的购物环境。同时，项目采用MySQL数据库进行数据存储，确保数据的安全性和稳定性。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于用户登录功能的核心代码：

```java
@RequestMapping(value = "/login", method = RequestMethod.POST)
public String login(String username, String password, Model model, HttpSession session) {
    User user = userService.findByUsername(username);
    if (user != null && user.getPassword().equals(password)) {
        session.setAttribute("user", user);
        return "redirect:/index";
    } else {
        model.addAttribute("message", "用户名或密码错误");
        return "login";
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

# 项目截图

![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/320641/34/26134/91755/689eaa65Fbbffae57/e89b36c2666273f3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/314202/27/26239/19714/689eaa4bF9238e0cf/e74d653ec77812ab.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/307541/36/26611/22222/689eaa4bF07335f5a/ce2a80c5d0882d6e.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/314625/9/25984/38666/689eaa4cF9dc3bb98/a59f5f0eb161265f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/310360/21/26214/24554/689eaa4dF3101e29e/00bc31632b1fa0b2.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/318848/7/24634/27717/689eaa4dF9afad541/78ad4400e2668ce7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/321114/14/25171/25107/689eaa4eF90a8f916/83787362460d26f4.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/319697/26/25216/55031/689eaa4eF73bd5267/becd7ec782d06723.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325005/9/4723/55975/689eaa4eF71f070a3/d05efb301518a309.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/315179/4/26547/17972/689eaa4fFec6755e1/36ac841821222d16.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
