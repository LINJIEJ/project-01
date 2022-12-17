## git config --list --global 查看所有的全局配置项

## git config user.name 查看指定的全局配置项

## git config --global user.name "输入用户名" //配置用户信息

## git init 初始化本地版本库

## git status 查看文件状态

## git status -s 以精简方式查看文件状态

## git add 文件名 //跟踪该文件，将该文件放入暂存区

## git add .  将所有未追踪文件放入暂存区

## git commit -m "提交消息"  //将已暂存的文件提交到git仓库

## git commit -a -m "提交消息"  //将修改后的文件跳过暂存区将其提交到git仓库

## git reset HEAD 要移除的文件名称   //从暂存区中移除对应的文件

## git reset HEAD .   //从暂存区中移除所有的文件

## git checkout --文件名   //将工作区修改后的文件还原成git仓库所保存的版本

## git rm -f 文件名   //从git仓库和工作区中同时移除该文件

## git rm --cached 文件名   //只从git仓库中移除该文件，但保留工作区中的该文件

## git log 展示所有的提交历史

## git log --pretty=onrline  在一行上展示所有的提交历史

## git reset --hard <commitID>  //根据指定的ID回退到指定的版本

## git reflog --pretty=oneline  //当回退版本后可通过该命令查看回退之前的所有提交历史

## git reset --hard <commitID>  //再次根据指定的ID跳转到最新的版本

## git remote add origin https://github.com/LINJIEJ/...  //将本地仓库和远程仓库进行关联，并把远程仓库命名为origin

## git push -u origin master  //将本地仓库中的内容推送到远程的origin仓库中，第一次将文件推送到远程仓库中必须执行该命令

## git push  //将本地仓库中新创建的文件推送到远程仓库中，只有第二次或以后的新建文件才能执行改简便命令

## ssh-key-t rsa -b 4096 -C "2432693995@qq.com"  //生成ssh key，连续敲击三次回车键，即可在C:\User\用户名文件夹\.ssh目录中生成id_rsa(私钥文件，存放于客户端的电脑)和id_rsa.pub(公钥文件，配置到Github中)两个文件
