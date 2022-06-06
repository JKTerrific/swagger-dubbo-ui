# swagger-dubbo-ui

支持 Dubbo2x版本的api接口文档
对swagger-dubbo组件的定制化swagger-ui界面。

解决了原始swagger-ui的一些问题：
  - 1. 解决了  Byte以及Date等类型无法直观的使用它们本身的类型展示的问题。
  - 2. 解决了  BodyParameter 在原UI界面是以input输入框形式存在并且无参数可视化JSON的问题。
  - 3. 解决了  BodyParameter 无法点击右侧json可视化例子复制进输入框的问题
  
如何使用？
直接将dist放在tomcat等web服务器的目录下即可访问到

swagger-dubbo 文档工程移步 https://github.com/Sayi/swagger-dubbo

部分界面如下
>接口截图
![Alt text](https://github.com/JKTerrific/swagger-dubbo-ui/blob/master/screenpic/picP1.jpg)


>返回对象截图
![Alt text](https://github.com/JKTerrific/swagger-dubbo-ui/blob/master/screenpic/picP2.png)


>入参截图
![Alt text](https://github.com/JKTerrific/swagger-dubbo-ui/blob/master/screenpic/picP3.png)


>入参案例截图<br>
![Alt text](https://github.com/JKTerrific/swagger-dubbo-ui/blob/master/screenpic/picP4.png)
