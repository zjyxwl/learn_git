- Git 是什么
    版本控制能力
        1. 提交到github 备份
            多个地方存 本地仓库
            远程仓库
        2. 一个文件， 返回修改， 文件文本
            精细化你这次改了哪一行
    1. 将项目变成支持版本控制项目
        git init
        -  .git 隐藏目录
            文件的每次修改， 都像拍照一样 放到 .git 目录下
            专业的 不要乱动
        - 默认仓库 master
        - 支持随时参看一个文件中的任何一个版本 很重要
        - .git 本地仓库   2步骤 慎重
            *0+
            git add readme.md   暂存
            git commit -m '(备注)'   仓库
        - git log 命令
            hashID 唯一值  git config --global user.name "zjyxwl"
            master 仓库  默认仓库

        - git status 当前仓库的状态
        .git local 
        remote github/gitee  代码安全 还有多人协作
    git remote add origin https://github.com/zjyxwl/learn_git.git