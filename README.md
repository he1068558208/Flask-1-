1.flask

flask 微框架

pip install flask

django-->完善完整高集成的框架

flask-->微框架，database，templates需要自己去组装


2.安装

创建虚拟环境virtualenv --no-site-packages flaskenv

	cd flaskenv
	
	cd Scripts

	activate

	pip install flask

3.运行flask

python xxx.py --->启动默认127.0.0.1:5000

4.运行参数

debug=True  调试

port ='8000'  端口

host = '0.0.0.0'  IP

5.修改启动方式

pip install flask-script

python hello.py runserver -p 端口 -h IP -d -r

6.蓝图--管理url ,规划url

pip install flask-blueprint

a)初始化
b)路由注册

7.route规则

django中
	\(\d+)\
	\<?p(d+)>\
  
flask中
	<converter:name>

	string:字符串
	
	int:整型

	float:浮点数型

	path:当成字符串类型返回
