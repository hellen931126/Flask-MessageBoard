# MessageBoard
演示：(不久可能会失效)[吐点槽吧](http://cumt.studio/)		
		
项目结构
```
|- app
	|- auth 用户模块
		|- __init__.py
		|- forms.py
		|- views.py
	|- main 
		|- __init__.py
		|- errors.py
		|- forms.py
		|- views.py
	|- satatic
		favicon.gif
		styles.css
	|- templates
		|- auth 用户
			|- change_password.html 
			|- login.html
			|- register.html
		|- 403.html
		|- 404.html
		|- 500.html
		|- _comments.html
		|- _macros.html
		|- _posts.html
		|- base.html
		|- edit_post.html
		|- edit_profile.html
		|- error_page.html
		|- index.html
		|- post.html
		|- upload_file.html
		|- user.html
	|- upload 文件上传
		|- avatar 用户头像
	|- __init__.py 初始化app文件
	|- email.py email配置以及异步实现
	|- exceptions.py 异常处理	
	|- models.py 数据库模型	
|- config.py 配置文件
|- manage.py run文件
```

后端考核任务

《吐槽》

根据狗书假期修改版

- 增加头像自定义,文件上传部分可拓展

- 增加一问一答形式回复功能,游客功能以及游客评论不能发布吐槽

- 增加新评论邮件推送管理员