Problem System 2.0 update content:

For the complete please visit(due to the file size limit of Github):
https://drive.google.com/open?id=1Bu2pzc-XH849z9mUZS1MXatxWE8ZSVo1

1. Modify the SQL that extracts the description information from the 
http://dbpedia.org website; make the describe more detailed.

2. Introduce Stanford University's NLP code to implement a problem pool for intelligent generation problems.


Startup method:

1. First put the two folders "config" and "dict" in the root directory of the compressed package into the apache-tomcat-8.5.34\bin\ directory of the computer.

2. Replace the program WAR package.

3. Double-click the runStanfordParserServer.bat script in the StanfordParserServer folder.
Start stanford's resolution service (less time for each startup, development port, direct access);
Display: "Waiting for Connection on Port: 5556" is the startup success;

4, start the apache server to load the main program.

note:
Because the current problem generation is resolved by stanford's service. So the process of generating the problem can be very long.
When you query the detailed description, the network speed is not good, and a white page will appear. Wait a moment.


问题系统2.0更新内容：

	1、修改从http://dbpedia.org网站拉取描述信息的SQL；使describe更加详细，丰富。
	2、引入斯坦福大学的NLP代码，实现智能生成问题的问题池。


启动方式：
	1、首先将压缩包根目录下的“config ”和“dict”这两个文件夹放入电脑的apache-tomcat-8.5.34\bin\目录内。
	2、替换程序WAR包。
	3、双击“StanfordParserServer”文件夹下的runStanfordParserServer.bat脚本，
	     启动stanfu的解析服务（较少每次启动的时间，开发端口，直接访问）; 
	     显示：“Waiting for Connection on Port: 5556”即是启动成功；
	4、启动apache服务器加载主程序。

注意：
	由于目前问题生成是靠stanfu的服务解析的。所以生成问题的过程会很长。
	另查询详细描述时，网速不好，会出现白页，稍等后就可以。