
### 项目结构


```
.\Child-Test
│
├─data                              
│  ├─fakers.json                    // 导航说明页使用的fake数据
│  └─fakers2.json                   // 真正的打分页使用的fake数据
│
├─css
│  ├─colored-theme.min.css          // 气泡弹窗的主题样式
│  └─driver.min.css                 // 导航说明的主题样式
│
├─js
│  ├─jquery.min.js                  // 本项目使用了jQuery对元素进行操作
│  ├─jqmodel.js                     // 引入轻量的模态框（弹窗）插件
│  ├─avataaars.js                   // 引入头像生成插件
│  ├─driver.min.js                  // 引入导航说明插件
│  └─growl-notification.min.js      // 引入气泡弹窗插件
│
├─partial
│  ├─intro.html                     // 主要实现了准备工作+打分页导航说明
│  ├─itact.html                     // 主要实现了打分页的生成及交互（区分实验组别）
│  └─cball.html                     // 玩球游戏，后经iframe独立引入Qualtrics
│
├─style.css                         // 网站基础样式
├─index.html                        // 认识人网的主页/入口
├─simple-http-server.exe            // 轻量的http-server启动器
└─README.md                         // 项目说明

```



### 快速使用

为了便于非开发人员自行使用，项目文件中已内置server启动器，无需安装任何编程环境和软件。部署步骤如下：

1. 下载当前项目（通过 `git clone` 或直接网页下载zip解压成文件夹均可）；

2. 打开命令提示符工具（Powershell也可）；

3. 更改当前目录到本项目的根目录，例如本项目文件夹放置在 `D` 盘 `D:\Child-Test`， 则拷贝执行 `cd /D D:\Child-Test` 命令；

4. 拷贝执行 `.\simple-http-server.exe --ip 127.0.0.1` 命令，启动服务；

5. 如下图所示表示运行正常，可点击访问 `http://127.0.0.1:8000/index.html` 随即进入认识人网页面。
![demo](https://cdn.jsdelivr.net/gh/zonelyn/img/demo.jpg)
