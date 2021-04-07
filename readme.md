### 这是我的第一个git案例
`git init` #初始化仓库
`git config -global user.name "xxx"` #配置仓库用户信息
`git config -global user.email "xxx@xxx"` #配置仓库邮箱
`git add ./xxx`  #添加所要备份的文件
`git commit -m "这是修改说明"`  #把文件放入仓库中
`git status` #查看当前状态 
`git commit --all -m "这是修改说明"` # 当前所有修改过的文件都放入仓库
`git log` #查看日志
`git log --oneline` #精简版log
`git reset --hard Head~0` #回退上一次提交的状态 -回退
`git reset --hard Head~1` #回退上上次提交的状态 -回退+1
`git reset --hard [版本号]` #精确回退对应的版本号
`git reflog` #可以看到每一次切换版本记录
## 分支
- `git branch [分支名]`
# 查看分支
- `git branch`
## 切换分支
- `git checkout [分支名]`
## 合并分支
- `git merge [分支名]`
## push github远程服务器仓库 
`git push https:github.com/xxx.git master` 
## 用SSH生成公钥 ->在电脑 C:\xxx\.ssh\id_rsa.pub  在个人的github上把公钥复制上去即可
` ssh-keygen -t rsa -C "邮箱地址" `
## 使用 
`git push git@github.com:xxx/xxx.git master`

