# ERP
![](https://img.shields.io/badge/language-php-orange.svg)
### 程序说明
开源的ERP进存销系统
<div>1.程序测试环境：</div><div><ul><li>&nbsp; Wamp64（Apache2.4.17+MySQL5.7.9+PHP5.6.16）</li><li>Php高版本可能出现不兼容</li></ul></div><div>2.程序运行说明：</div><div><ul><li>将文件解压到网站根目录wamp中在www目录下</li><li>Navicat 新建数据库名为 webtest ，然后导入System.sql。</li><li>导入完成后存在两个用户，存放于ci_admin 表中，可以查看，密码经过加密。用户：admin 密码：admin123456</li></ul></div><div>3.登陆系统<br><ul><li>如果登录时出现用户名或密码错误，可能是没有正确连接数据库，在application/config/database.php中修改数据库参数设置，改成与你自己的</li></ul></div>
