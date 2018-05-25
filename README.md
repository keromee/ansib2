文件夹结构
	defaults 默认寻找路径
	tasks 存放playbooks路径
	files 存放文件和脚本，copy模块文件搜索路径
	templates 模版存放路径
	handlers notify调用部分playbook存放路径
	vars roles内变量存放路径

文件夹生成 快速安装
mkdir -p xx/ansible/roles/{nginx,mysql,tomcat,db}/{defaults,files,handlers,meta,tasks,templates,vars}

安装前请先确认
	配置好两张网卡并记录好网卡名
	ELEP源已安装并update软件源
	根据实际环境调整lib目录的相关配置
	cinder时请确认是否已有盘sdb1

参考：http://www.jianshu.com/p/c62fb92fb23f