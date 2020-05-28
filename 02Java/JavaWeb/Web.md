## Web概念

>   使用 Java 语言开发基于互联网的项目

## 软件架构

1.  C/S: 客户端/服务器端

    优点：增强用户体验

    缺点：开发，安装，部署，维护 麻烦

2.  B/S:  浏览器/服务器

    优点：开发，安装，部署，维护 简单

    缺点：

    ​	如果应用过大，用户体验差

    ​	对硬件要求过高



### B/S 架构详解

#### 资源分类：

1. 静态资源：
  >   使用静态网页开发技术发布的资源。

  特点：
  * 所有用户访问，得到的结果是一样的。
  * 如：文本，图片，音频、视频, HTML,CSS,JavaScript
  * 如果用户请求的是静态资源，那么服务器会直接将静态资源发送给浏览器。浏览器中内置了静态资源的解析引擎，可以展示静态资源
2. 动态资源：
  >   使用动态网页及时发布的资源。

  特点：
  * 所有用户访问，得到的结果可能不一样。
  * 如：jsp/servlet,php,asp...
  * 如果用户请求的是动态资源，那么服务器会执行动态资源，转换为静态资源，再发送给浏览器


