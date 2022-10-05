…or create a new repository on the command line
echo "# RE01" >> README.md
git init
git add README.md
git commit -m "first commit"

# 创建一个 main 分支，并把主分支切换为 main

git branch -M main

# 给这个 git 项目设置一个仓库地址（网盘地址）

git remote add origin https://github.com/cdtiandi/RE01.git

# 推送上传至网盘

git push -u origin main

…or push an existing repository from the command line
git remote add origin https://github.com/cdtiandi/RE01.git
git branch -M main
git push -u origin main

…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
