## 课时3 git的基本操作
    01.介绍
        -GitHub是一个面向开源及私胡软件项目的插管平台，因为只支持Git作为唯一的版本库格式进行托管，故名GitHub。

        -Git是一款免费，开源的分布式版本控制系统，用于敏捷高效的处理任何小域大的项目。

        -和大家一起熟悉GitHub和Git的基本使用

        -使用Git快速参与项目开发


    02.跳上github这艘大船
        -基本的账号注册
        -找到些流行的开源框架项目、获取第一手资料
        -follow一些技术牛人，持续关注他们的动态，以及关注一些感兴趣的项目
        -创建仓库，以及github上可对项目的基本操作
        -未来是否你也有兴趣参与开源

        第一步：注册

    1.github的注册
            01. 在浏览器地址栏中输入：https://github.com/join
            02. 注册信息输入
                Username: 输入用户名"只能是英文和数字"
                Email Address: 输入邮箱地址
                Password: 输入密码
            03. Create an account 点击创建

    2.创建仓库           

        01.点击右边的的按钮：New repository
        02.创建项目、目录
            Repository name： 以下的input框中输入项目、目录的名字为英文
            Description (optional)：描述项目的说明
            Public：选择公开的
            Initialize this repository with a README：这里如果选择上了，就会在你的项目下面创建两个文件
        03.Create repository  点击 创建库

        04.克隆项目地址下来
            $ git clone https://github.com/loungcingzeon/react-201704.git  这里要克隆项目的路径


    3-下载:http://git-scm.com/downloads

      -基本的config
          -username & email

      -创建仓库
          -init or clone

      -git基本操作
          [enter image description here]
          (http://www.ruanyifeng.com/blogimg/asset/2015/bg2015120901.png)


          $ git --help                                    查看帮助文件，和如何使用

          // git 本地基本配置信息，
              $ git config --golbal user.name "loungcingzeon"            配置全局用户名     loungcingzeon这是自己的用户名
              $ git config --golbal user.email "loungcingzeon@sina.com"  配置全局用的邮箱   loungcingzeon这是自己的邮箱名

          $ mkdir git-demos                               		创建一个文件夹
          $ git https://github.com/loungcingzeon/react-201704.git                         要克隆的地址        
          $ git status                                    		查看状态      
          $ git add -A                            		        把全部文件添加到暂存区
   	  $ git status                                    		查看状态    
          $ git commit -m"描述"                           		添加提交文件的说明
          $ git push origin master                        		把文件提交到远程仓库上面去

          接下来就是要要求你输入你的用户名和密码, 最后就提交成功
