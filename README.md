# springcloud-config
springcloud-config

本地git 命令行提交命令：
1. cd 进入当前目录
2. git add .             #添加所有修改的文件
3. git status            #查看git当前的状态

            n branch main
            Your branch is up to date with 'origin/main'.     # origin  代表当前用户 ， main 代表当前在主分支

            Changes to be committed:
            (use "git restore --staged <file>..." to unstage)
                new file:   application.yml                  # 代表新增了文件 application.yml

4. git commit -m "msg"   # 提交到本地                          # msg ：提交的信息

            [main 08f2b23] first commit for application.yml
            1 file changed, 17 insertions(+)
            reate mode 100644 application.yml

5. git push origin main  # 推到远程git仓库                     # 代表当前用户 push到main分支

            Enumerating objects: 4, done.
            Counting objects: 100% (4/4), done.
            Delta compression using up to 8 threads
            Compressing objects: 100% (3/3), done.