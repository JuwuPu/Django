
 # 1.1 Django introduction
 
 ## 1.01
 - 组件：
  - 基本配置文件/路由系统
  - 模型层（M）/模版层（T）/视图层（V）
  - Cookies 和 Session
  - 分页及发邮件
  - Admin管理后台


- 用途：
  - 网站/微信公众号/小程序后端开发
  - 人工智能平台融合

安装Django
```
pip3 install django==2.2.12
```


检查是否安装成功
```
sudo pip3 freeze | grep -i 'Django'
```

## 1.02 项目结构1
### 创建项目
- 成功安装Django后，使用命令 `django-admin`;
- 执行`django-admin startporject projectnanme`创建出对应项目文件夹；

### 启动服务
- 启动【测试开发阶段】
 - 终端cd进入项目文件夹
 - 进入项目文件夹后，执行`python3 manage.py runserver` 启动Django服务【注：该启动下，Django在前台启动服u，默认监听8000端口】
 - 浏览器访问 http://127.0.0.1:8000/ 可以看到Django的启动页面
 - 注：如果想更换端口，则可以用 `python3 manage.py renserver port`
