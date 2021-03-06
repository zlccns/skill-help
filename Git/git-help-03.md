# Git 创建版本库

当我们成功安装 git 之后，就可以创建本地仓库并且使用了。

首先，选择一个合适的地方，创建一个空文件夹，而该文件夹将作为你的 git 仓库，未来这个目录里的所有文件都将通过 git 去管理 ：

```bash
# 第一步：创建文件夹
mkdir test
# 第二步：进入文件夹
cd test
# 第三步：创建一个文件 README.md，内容为 '# Hello World'，并保存
echo "# Hello World" >> README.md
# 第四步：初始化项目，把这个目录变成Git可以管理的仓库
git init
# 第五步：用命令告诉Git，把文件添加到仓库
git add README.md
# 第六步：用命令告诉Git，把文件提交到仓库
git commit -m "书写修改内容标题"
```

##### 特别注意

`第四步：git init`：当你执行到第四步时，当前目录下会自动生成一个 `git` 的隐藏文件夹，该文件夹保存了 Git 的所有内容，**轻易不可修改，误操作将会导致整个仓库出现损坏**

```bash
# 打印当前目录下的所有内容，包括隐藏文件夹
$ ls -ah
# .git 即为隐藏文件夹
.		..		.git		README.md
```
