打开终端git base
$ git clone https://github.com/5xiao/Tdwy
$ cd Tdwy

$ echo '.idea' >> .gitignore
$ git rm -r --cached .idea
$ git add .gitignore
$ git commit -m '(some message stating you added .idea to ignored entries)'
$ git push
如果报错:! [rejected]        master -> master (fetch first)
使用下面的命令

git push -f origin master  强制推送