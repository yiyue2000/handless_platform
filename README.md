# handless_platform
这是我的毕设项目。搭建一个小小的傻瓜平台 demo

#### 一、目前的简单规划：
1. 将整个编辑器的框架搭建出来（使用的基本工具配置好，功能定义好）
2. 设计 schema（渲染的功能表）


**2022-3-10 周四**
1. 今天使用 vite 来把自己的 项目 start up 了，之前还在琢磨 webpack + react 来着
2. 安装了 react-router，能实现路由跳转功能了。
- 发现问题：默认安装的是最新版的 react-router-dom 6，但是看的文档是 react-router 5 的内容。并且中文文档是有延时的……给的例子也不对
- 后面去理解一下具体组件的用法吧
- 有点憨憨，忘记打开控制台看看到底啥问题（有没有报错），折腾老半天
3. 使用了 antd 来构建整个的 layout 主布局。（对 antd 不是很熟悉……）
4. antd 没有样式：需要在 root 文件中添加： `import 'antd/dist/antd.min.css'`
(好怪啊，需要我自己导入 style 吗？为什么呢？）
