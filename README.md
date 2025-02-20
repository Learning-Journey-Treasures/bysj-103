# 1.项目介绍
- 系统角色：管理员、员工(自定义设置名称和菜单权限，比如HR，经理、销售总监等)
- 功能模块：薪资管理（五险一金、参保城市、工资管理）、权限管理（角色管理、菜单管理）、系统管理、考勤管理（请假审批、考勤表现）等
- 技术选型：SpringBoot，Vue，element-ui等
- 测试环境：idea2024，jdk1.8，mysql5.7，maven3，Node14.16.1等
# 2.项目部署
## 2.1 后端部署
- 创建数据库，导入sql文件
- idea打开目录hrm，根据本地数据库环境修改src/main/resources/application.yml 7-10行
- 将file目录copy到D盘，如果没有D盘，请修改src/main/resources/application.yml  27行
- 启动项目src/main/java/com/hrm/HrmApplication.java
## 2.2 管理web
- idea（安装vue.js插件）或者webstorm、vscode等ide工具打开项目vue-elementui-hrm
- 进入终端，输入 yarn  install安装依赖（百度安装yarn，下载失败自行配置阿里的镜像加速）
- 启动项目 yarn serve
- 打开终端的地址，输入账号密码：管理员（admin、123456）、普通员工（staff_3, 123456）,其他自行查表
# 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.jpg)
![输入图片说明](3.jpg)
![输入图片说明](4.jpg)
![输入图片说明](5.jpg)
![输入图片说明](6.jpg)
![输入图片说明](7.jpg)
![输入图片说明](8.jpg)

# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)
