![](https://github.com/AIRobotZhang/PostBar/raw/master/pic.png)  

这是工大吧1.0版本，目前实现的功能有：注册、登录、发布问答、查询、评论

1.在进行该项目之前，必须安装 Flask 以及一些我们会用到的扩展。首选的方式就是创建一个虚拟环境 ,这个环境能够安装所有的东西，而此时我们的主Python不会受到影响。另外一个好处就是这种方式不需要我们拥有root权限。具体参考网站：http://www.pythondoc.com/flask-mega-tutorial/helloworld.html

2.该项目中需要用到SQLAlchemy，它提供了SQL工具包及对象关系映射（ORM）工具，将数据可视化，并与数据库相关联

3.该项目采用的是MySQL数据库(Server version:5.7.19 MySQL Community Server),需要首先创建需要用到的数据库，如本实验的hitqa数据库

4.在models.py文件中是数据模型，当增添新的数据模型时，需要将其重新映射到数据库中，步骤如下：
  首先进入虚拟环境的命令环境下，其次，进入到manage.py项目文件目录下，依次在命令行窗口下执行如下两条命令：python manage.py db migrate 和 python manage.py db upgrade ,映射成功，可到数据库命令行窗口查看
 
 具体效果图：
 ![](https://github.com/AIRobotZhang/PostBar/raw/master/register.png)  
 
 ![](https://github.com/AIRobotZhang/PostBar/raw/master/login.png)  
 
 ![](https://github.com/AIRobotZhang/PostBar/raw/master/question.png)  
 
 ![](https://github.com/AIRobotZhang/PostBar/raw/master/first_page.png)  
 
 ![](https://github.com/AIRobotZhang/PostBar/raw/master/answer.png)  





