# flask_blog2
flask 1.0.2 官网示例
使用命令行模式进行应用的启动，否则会出现各种错误。                                                                                             
项目基本与官方文档一样，其中注册视图有修改（官方实现注册成功后，直接跳转登陆页面；我修改为：注册成功后，修改为登陆状态，并跳转到首页）                 
在 Linux and Mac 下：                                                                                                                      
export FLASK_APP=flaskr                                                                                                                   
export FLASK_ENV=development                                                                                                               
flask run                                                                                                                                 
在 Windows 下，使用 set 代替 export ：
set FLASK_APP=flaskr                                                                                                                       
set FLASK_ENV=development                                                                                                                 
flask run                                                                                                                                 
在 Windows PowerShell 下，使用 $env: 代替 export ：                                                                                         
$env:FLASK_APP = "flaskr"                                                                                                                 
$env:FLASK_ENV = "development"                                                                                                             
flask run
