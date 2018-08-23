# git-teamwork
1. fork项目，参与开发，fork后会在你的主页建立一个同名仓库；
2. git clone 你fork的仓库地址  到本地
3. 修改本地文件commit，push
4. pr
自己开始也是这样的，但是后面如果作者更新了，你这边还是原来的代码的话就跟不上进度，所以必须要同步其他人的进度

1. git remote add upstream 你fork项目的原始地址   （作用是保存项目地址通过upstream来代替，不需要每次都输入这个地址）
2. git pull upstream 分支名   （拉取项目的最新代码到本地，保持同步）
3. 编辑你自己的代码,commit,push
4. 如果你需要合并自己的commit记录，可以使用git rebase -i head~3 (最近3次的提交记录)
5. 按i进入插入模式然后可以根据提示编写commit，然后esc退出模式再按:wq退出保存
6. git push --force 提交代码
7. 可以安安心心的pr了，然后等着merge或者rebase
