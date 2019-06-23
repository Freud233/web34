## git
+ 初始化git仓库 git init
+ 查看仓库状态 git status
### 关联现有本地仓库
1. git remote add origin git@github.com:Freud233/web34.git
2. git push -u origin master
### 本地仓库内容推送到远程仓库
1. git add .  // 所有文件添加到工作区
2. git commit -m '' // 添加详细说明 
### 生成密钥
+ ssh-keygen -t rsa -C "humingx@yeah.net"
+ 找到密钥 cat ~/.ssh/id_rsa.pub
### 配对密钥
1. github 设置
2. SSH and GPG keys  
3. New SSH key
4. 添加刚刚生成的密钥