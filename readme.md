
# GIT使用

工作区 - 暂存区 - 本地仓库

1. 在电脑上创建一个文件夹作为工作区
2. 打开文件夹右键 git base here 进入当前目录
3. 工作区持有项目实际文件
4. 暂存区和本地仓库 不需要我们操作！！

## readme 文档
1. readme文件可以txt文档，也可以是md文档
2. 一般和项目放在一起，作为项目的说明文档

## 全局配置
1. 配置用户名：git config --global user.name "你的git名称"
2. 配置用户邮箱：git config --global user.email "你的git验证邮箱"
3. 一台电脑配置一次就可以了
4. 查看你的配置信息：git config --list

## 初始化
1. 命令 git init 初始化版本库
2. 当前目录路径后面有(master)代表初始化成功
3. 在当前目录下会生成一个隐藏文件 .git 代表这是一个版本库
4. 千万别操作 .git 文件，让他隐藏不管它

## 工作区内容提交到本地仓库
1. 执行命令 git add 文件名 将工作区的内容提交到暂存区
2. 命令 git add . 将所有变动（新增、修改、删除）提交到暂存区
3. 从暂存区提交到本地仓库 git commit -m '提交注释'

## 版本回退
1. 命令：git reset --hard HEAD^  回退到上一个版本（一个^代表上一个版本）
2. 命令：git reset --hard 版本号  回退到指定版本

## 辅助命令
1. 命令 git status 查看当前目录下的操作状态
2. git log 查看日志
3. git reflog 查看简版日志


