# 简介

---

本测试教程主要用于gitbook学习与测试，参考[教程](http://www.chengweiyang.cn/gitbook/index.html)

主要章节如下：
* [4.3.2 GitHub集成](http://www.chengweiyang.cn/gitbook/gitbook.com/config/github.html)
* [4.3.3 绑定域名](http://www.chengweiyang.cn/gitbook/gitbook.com/config/domain.html)

### 正文

##### 安装
```powershell
npm install -g gitbook-cli
```

##### 使用([参考](http://www.chengweiyang.cn/gitbook/basic-usage/README.html))
    1 使用`gitbook init`初始化书籍目录
    2 使用`gitbook serve`启动服务
    3 使用`gitbool build`编译代码

##### GitHub集成
    1 首先本地创建gitbook项目
    2 github创建repository并将本地项目push上去
    3 进入gitbook.com注册账号，并创建book（项目）
    4 进入book设置，绑定github，输入github repo（格式为用户名/repo名）
    5 如果同步的时候出错，一定要选择同步到github项目，不要选择gitbook
    
##### 绑定域名
    1 在GitBook官网的book设置页面，选中Domains（域名），在Domain for content（内容中）输入需要的域名比如book.xxx.com，
    点击保存。这时可能提示绑定出错，因为该域名还没有解析。
    2 将book.xxx.com绑定到CNAME，主机记录为book，记录值为www.gitbooks.io，保存并启用，一般至少需要10分钟才能生效


