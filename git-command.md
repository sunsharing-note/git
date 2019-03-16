```
git --version 查看git版本号
git config --global uer.name gw 设定用户名
git config --global user.email 40634341@qq.com 设定邮箱
git config --global color.ui true 设置高亮
git config --list 配置列表
git init 初始化
git status 查看当前状态
git add xxx 上传到暂存区
git commit -m "add file " 提交 -m 描述
git reset HEAD b 删除
git checkout -- b 撤销 把暂存区文件覆盖工作目录的文件
git mv b b.txt git文件改名
git add . 把工作目录所有文件提交到暂存区
git rm --cached b.txt 删除暂存区文件
git rm -f 同时删除工作目录和暂存区
git diff 比对暂存区和工作区
git diff --cached 比对暂存区和本地仓库
git log 已提交本地仓库文件的记录
git log -p 查看每次提交具体内容
git log --oneline 一条命令显示提交文件的记录
git log --oneline --decorate 看head指向
git reflog 所有提交的历史记录
git reset --hard ee73276恢复快照
git branch 查看分支
git branch 名称 创建分支
git checkout 名称 切换分支
git checkout -b 名称 直接创建并切换
git branch -d 名称 删除分支
git merge 分支名称 合并分支
git tag -a "v2.0" -m "merge dev " 给当前打标签
git tag 查看标签
git show v1.0 查看标签的内容
git tab -d v1.0 删除标签
```
