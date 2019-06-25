# Git Linux Command
## Git Repository
文件夹下有一个隐藏目录`.git`是Git的版本库</br>
![图解工作区与版本库](https://www.liaoxuefeng.com/files/attachments/919020037470528/0)</br>
我们把文件往Git版本库里添加的时候，是分两步执行的：</br>
第一步是用git add把文件添加进去，实际上就是把文件修改添加到暂存区；</br>
第二步是用git commit提交更改，实际上就是把暂存区的所有内容提交到当前分支。</br>
因为我们创建Git版本库时，Git自动为我们创建了唯一一个master分支，所以，现在，git commit就是往master分支上提交更改。</br>
你可以简单理解为，需要提交的文件修改通通放到暂存区，然后，一次性提交暂存区的所有修改。</br>
**1. git add**</br>
![git add](https://www.liaoxuefeng.com/files/attachments/919020074026336/0)</br>
**2. git commit**<br>
![git commit](https://www.liaoxuefeng.com/files/attachments/919020100829536/0)</br>
