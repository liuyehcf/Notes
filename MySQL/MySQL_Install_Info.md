## Mac平台下安装步骤
* 1) brew install mysql   <==会得到以下信息
>       We've installed your MySQL database without a root password. To secure it run:  
            mysql_secure_installation  
        To connect run:  
            mysql -uroot    
        To have launchd start mysql now and restart at login:  
            brew services start mysql  
        Or, if you don't want/need a background service you can just run:  
            mysql.server start  
* 2) 执行:mysql_secure_installation
>       设置root的密码  
        以及其他权限的设置
* 3) 于是就可以登录了
    		

## Window平台安装步骤
* 1) 解压缩.zip包
* 2) 在解压路径下新建文件"my.ini"(可以通过复制相同目录下的"my-default.ini"然后改名为"my.ini"完成)
* 3) 编辑"my.ini"文件，在末尾追加以下内容，假设文件夹路径为D:\mysql
>		[mysql]
		# 设置mysql客户端默认字符集
		default-character-set=utf8 
		[mysqld]
		#设置3306端口
		port = 3306 
		# 设置mysql的安装目录
		basedir=D:\mysql
		# 设置mysql数据库的数据的存放目录
		datadir=D:\mysql\data
		# 允许最大连接数
		max_connections=200
		# 服务端使用的字符集默认为8比特编码的latin1字符集
		character-set-server=utf8
		# 创建新表时将使用的默认存储引擎
		default-storage-engine=INNODB  

* 4) ***以管理员身份***打开CMD，并进入解压文件的bin目录，此处为D:\mysql\bin
* 5) 在DOS中输入:mysqld install(对应的删除命令为:mysqld remove)
* 6) 在DOS中输入:mysqld --initialize-insecure --user=mysql
        执行完后，MySQL会自动建立data文件夹，并建好默认数据库
        登录的用户名为root，密码为空
* 7) 在DOS中输入:net start mysql
* 8) 于是就可以登录了
* 9) 另外还可以将bin路径添加到环境变量path中
