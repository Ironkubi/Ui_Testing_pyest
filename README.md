<<<<<<< HEAD
# PytestUiAutoTest
=======
# PytestAutoTestFrameWork
    Pytest框架实战项目实例
    帮助：
        通过此项目可以学到以下内容
        1.命令行如何运行测试用例
        2.pytest如何收集测试用例
        3.如何使用fixture
        4.如何使用conftest.py文件
        5.如何使用pytest-html插件生成测试报告
        6.PO设计模式思想是什么样的
        7.selenium 部分API的使用和如何进行简单的二次封装
        9.pytest框架如何参数化测试用例
        10.如何发送测试报告邮件
        11.如何使用代码的方式执行测试用例或整个项目
        12.测试用例编写逻辑
    说明：
        1.本项目测试地址为126邮箱
        https://mail.126.com
        2.请先简单了解126邮箱的各个功能
        3.本人博客地址：https://www.cnblogs.com/linuxchao
    环境需求：
        1.windows 7 以上版本
        2.需安装python 3.以上版本
        3.selenium 2 以上版本
        4.需安装pytest框架
        5.需安装pytest -html插件
        6.需安装火狐或谷歌浏览器及对应驱动
        7.需对发送测试报告邮件的邮箱正确配置（可在我博客中找到相关配置文章）
        8.需要安装pypiwin32库
        9.需要安装openpyxl数据处理库
        10.需要安装yagmail库发送测试报告
    运行项目：
        1.下载项目到本地
        2.打开cmd切换到项目根目录
        3.输入python RunTestCase.py运行项目
        4.或者直接通过pytest --html=’report.html‘ 运行(这种方式不会自动发送测试邮件)
        5.或者在pycharm中打开项目，直接运行RunTestCase.py文件
    用例说明：
        请下载原代码自己查看用例具体测试了哪些功能
    
    修改说明：
        .修改了所有代码的编写规范，使其更加符合PEP8
        .由于126邮箱升级，因为修改了部分用例的逻辑，更加容易理解
        .所有的用例按照不同错误提示信息进行了分组
        .修改了测试数据的存储方式，由excel改为了使用py文件直接存储
        .添加了环境管理文件requirement.txt文件，方便clone本想的人能够顺利运行项目
        .注意！注意！注意！
        .测试数据中的126邮箱的用户名和密码是我本人的邮箱, 请不要做危害国家和我个人的事情，不要浪费我一翻辛苦，非常感谢！
         当然，你最好改为你自己的邮箱,否则你运行项目的时候我会平凡收到邮件
        .由于126邮箱有很多限制，坑比较多，比如你登录次数过多时会有验证码的提示(验证码比较难处理, 我未做处理)，所以如果
         有验证码提示了后面用例步骤就没办法执行了, 即使清楚cookies下次还是会提示，很烦, 所以我整个项目是多次打开浏览器的
         能够防止一下这种情况
        .还有一个限制是在发送邮件的时候，如果发送过多次数，也会有验证，我就不细说了，请自行体会吧
        .最后说一句，clone本项目后，最好为本项目建立的空白的虚拟环境， 然后在虚拟环境中使用pip install -r requirements.txt自动安装依赖
        
>>>>>>> origin/master
