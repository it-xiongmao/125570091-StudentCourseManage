



 **项目列表** ：[项目列表地址链接(点击即可查看)](https://nwqbsc0rm1n.feishu.cn/docx/KiipdQWF4oS9x0x7wfqcWGMrnOe?from=from_copylink)

**系统演示链接** ：[基于JavaEE学生选课系统项目演示](https://www.bilibili.com/video/BV1im4y1p7QP/?spm_id_from=333.999.0.0&vd_source=ce786491c0124e1afaad0343941f3499)

 **获取源码** ：微信搜索公众号【熊猫IT技术】回复项目编号： **125570091** 

## 1.项目简介
本系统是功能完善的学生选课管理系统，在本系统中，开发了一个面向管理员、学生和教师这三个对象的管理平台，对学生提供的服务有登录、选课、、修改登录密码、和查询成绩这几个服务，对教师提供的服务有登录、修改登录密码和登录成绩；对管理员提供的服务有登录开设学生和教师帐号、删除学生和教师帐号的服务。


系统中用户分为三种：

![在这里插入图片描述](https://img-blog.csdnimg.cn/53d60adcace54d898a682a169ee50639.jpeg#pic_center)


**测试账号**

```java
管理员：
     账号：root   密码：qwe123    登录地址：http://localhost:8080/pages/rootlogin.html
     
教师：
     账号：qwe3  密码：qwe123    登录地址：http://localhost:8080/pages/teachlogin.html

学生：
     账号：qwe1  密码：qwe123    登录地址：http://localhost:8080/pages/studentlogin.html
```

## 2.技术实现
- 数据库：MySQL
- 开发工具：IDEA或Eclipse
- 数据连接池：Druid
- Web容器：Apache Tomcat
- 版本控制工具：Git
- 项目构建工具：maven
- 后端技术：Servlet
- 前端框架：HTML、CSS、Jquery、LayUI

## 3.运行部分截图
系统首页：
![在这里插入图片描述](https://img-blog.csdnimg.cn/6bb18e00d140444e80c77cb61fe425f5.png)

### 4.1.管理员模块
管理员登录：
![在这里插入图片描述](https://img-blog.csdnimg.cn/8c0db00b49594794810627b3b847f053.png)
管理员首页：
![在这里插入图片描述](https://img-blog.csdnimg.cn/6b59d6761d704c438a73a29aee67f4b2.png)

账号审核：
![在这里插入图片描述](https://img-blog.csdnimg.cn/b69d48c9bc0d4cf8b3afde128527a6de.png)

![在这里插入图片描述](https://img-blog.csdnimg.cn/bf46657d151b4590a7abb07cdb5d2a53.png)


权限管理:
![在这里插入图片描述](https://img-blog.csdnimg.cn/ff06005274724615ac7fc259066d9596.png)

角色编辑：
![在这里插入图片描述](https://img-blog.csdnimg.cn/ab55fdbe29f043c38bcdf068d280688b.png)

账号管理：
![在这里插入图片描述](https://img-blog.csdnimg.cn/9fac8003a366411c9559a24e82ec8b7e.png)

系统通知:
![在这里插入图片描述](https://img-blog.csdnimg.cn/9a703bf310514f5ba5ec12b8e6f8d24f.png)课程审核：
![在这里插入图片描述](https://img-blog.csdnimg.cn/a1ed642fd739473e8f3329c9f1830ea0.png)

###  4.2.教师模块
教师登录：

![在这里插入图片描述](https://img-blog.csdnimg.cn/76b80a22ee8748ea91549135efe265ff.png)

教师管理首页：
![在这里插入图片描述](https://img-blog.csdnimg.cn/387eaf28da7f4e80bf3b8c898f7191c4.png)

课程添加：
![在这里插入图片描述](https://img-blog.csdnimg.cn/c210c9fc4e484e60afd6ad8fe9e2e709.png)

课程查询：
![在这里插入图片描述](https://img-blog.csdnimg.cn/f2c4f54d2a8940aa8ae894e78fa85f8a.png)

上传成绩：
![在这里插入图片描述](https://img-blog.csdnimg.cn/d4a9ace41d9d4f2cabe1fe38c5942af2.png)

密码修改：
![在这里插入图片描述](https://img-blog.csdnimg.cn/118746135ead49bb95f5429ba5b17ace.png)
系统消息：
![在这里插入图片描述](https://img-blog.csdnimg.cn/d34f982c07a74da4ab5350cd9415e527.png)
###  4.3.学生模块
学生登录：
![在这里插入图片描述](https://img-blog.csdnimg.cn/cdffa9bcd33745768e50c35b49233de3.png)

学生首页：
![在这里插入图片描述](https://img-blog.csdnimg.cn/fad30ed3fbcc40c3b17664ea367b2bb7.png)

个人信息:
![在这里插入图片描述](https://img-blog.csdnimg.cn/3b48c08658d1472e816d9e3d4ecc364e.png)

我的选课：
![在这里插入图片描述](https://img-blog.csdnimg.cn/479a9118a50840c5a3c5b3256c6b0c7c.png)

网上选课：
![在这里插入图片描述](https://img-blog.csdnimg.cn/8b0d68b20d5c473ca31856f0be5ee961.png)
选课历史：
![在这里插入图片描述](https://img-blog.csdnimg.cn/75a4b8eb486b47ab90c6d2f29252fe7d.png)
系统消息：
![在这里插入图片描述](https://img-blog.csdnimg.cn/481a7b1ddd4a40189e2566fa53f548f9.png)

修改密码：
![在这里插入图片描述](https://img-blog.csdnimg.cn/786365ad4ef443b4b49d0d36cd01f1da.png)
## 5.源码获取

如需本系统完整源码请在微信搜索公众号【熊猫IT技术】 回复项目编号： **125570091** 
