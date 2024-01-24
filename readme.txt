Git is a distributed version control system.
Git is free software distributed under the GPL.
创建一个仓库create a repository（两步）
    $ mkdir learngit 
    $ cd learngit  #创建一个名为learngit的目录
    $ pwd   #显示当前目录
    
    $ git init  #目录learngit变成一个Git仓库（初始化）

添加文件至仓库  e.g. 仓库里有文件 "readme.txt"
    $ git add "readme.txt" #添加，将文件从工作区提交入暂存区
    $ git commit -m "xxx"  #提交，将文件从暂存区提交到当前分支
        -m后带注释
    $ git status  #工作区状态
    $ git diff "readme.txt"   #查看修改内容，后跟文件名（工作区），commit id（版本库），可不唯一
    $ git log     #显示所有的提交日志
        --pretty=oneline  #参数，按行显示
    $ git reflog  #显示命令历史

Git 最强大的地方：回退
    $ git reset --hard HEAD^  #回退or回溯至某版本（用commit的id或者HEAD）
    


    

