# git 教程

## git Basics
第一章就介绍完所有的常用的基础的命令

### Getting a Git Repository
1. git init
This creates a new subdirectory named .git that contains all of your necessary repository files – a Git repository skeleton. At this point, nothing in your project is tracked yet. 
会生成一个自动的代码库，这个代码库中间的git文件就是git core的内容

2. git add
这就是加上这个文件使得这个文件开始被track

3. git commit -m "commit content'
这个就是把追踪的文件提交到git中
3.1. git commit --amend：可以撤销上一次的提交，然后加上忘掉的文件，重新提交一次

4. git clone .git
这个是从一个git网上库下载到本地

### Recording Changes to the Repository
5. git status
可以看到当前add的文件和没有被add的文件
但是当被commit之后就不需要了

6. git diff
现在来阐述一下如何比较两个版本的文件

7. git mv
git mv是真的

8. git rm
也是真的删除

### Viewing the Commit History
9. git log
就是查看git所有的commit的
这个命令有很多的功能，有筛选机制

### Working with Remotes
10. git remote
git remote -v可以看到非常详细的信息

