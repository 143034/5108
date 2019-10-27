# scrapy_paper
软件目的:爬取相关论文网站的信息


首先运行"配置环境.exe",鼠标左键双击,或者将search.json和three.json复制到D盘的主目录下。

linux用户直接运行cralw1.py即可

windows用户找到并运行dist菜单下的cralw1.exe


软件使用说明:



	菜单选项

		设置:
			关于作者
			退出

		scrapy:
			选择爬虫
			三大顶会
			爬取结果展示

		搜索:
			搜索

		帮助:
			帮助

使用说明:
		具体请看paper.jpg文件

实现步骤:

		1.ACM,CNKI,spring爬虫的编写


		2.tk.py的编写


		3.使用keywords.py,three.json,search.json对爬虫关键词进行控制


		4.编写cralw1.py引入scrapy相关的模块和tk.py


		5.使用pyinstaller对cralw1.py进行打包,生成相应的cralw1.exe,需要在dist/cralw1目录下建立scrapy文件并复制python源码中的mime.types和VERSION文件到该目录下


		6.执行cralw1.exe











