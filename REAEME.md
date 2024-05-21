# Test

初始化 git 仓库：git init.

将一个文件纳入跟踪/将一个文件的修改提交到缓冲区：git add <path/to/the/file/or/dir>

提交：`git commit`，然后填写 commit message，保存并退出.

修改 git 提交的用户名和邮箱

```bash
git config --global user.name <name>
git config --global user.email <email>
```

ggg

hhh

ZSH 中 git 操作简写:

```zsh
ga -> git add
gc -> git commit
gc! -> git commit --amend
gcm -> git checkout master
gco -> git checkout
```

git 新建分支：`git checkout -b <branch_name>`

切换分支：`git checkout <branch_name>`