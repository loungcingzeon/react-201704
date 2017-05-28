## 创建分支,  "branch_name"是自己定义的分支名
        $ git branch branch_name    

    # 本地切换到这个分支 也就是branch_name
        $ git checkout branch_name  


    # 创建并且直接切换到这个新分支
        $ git checkout -b branch_name

    # 分支合并，比如新分支 develop合并到master分支
        01.创建一个分支，名为 develop
            $ git branch develop
        02.切换到这个develop的分支
            $ git checkout develop

        03.合并分支，把develop 合并到 master 下面
            $ git merge master devlop

        04.查看远程的分支
            $ git branch

        05.上传内容到 develop 的分支上去
            $ git push origin develop

        06.拉取 develop 的分支内容下来
            $ git pull origin develop
