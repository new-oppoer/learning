# learning
programing
Hi,I'm Brown!
I'm learning coding.

### git 

`git config ` 	about user's configuration file 

`git init` init the repository

`git clone` clone an existed repository

`git status`   check the file state

`git status -s`  output in more simple format

`git diff` 	check untaged modified part 

`git diff --cahed`  check  staged part differences

`git rm`		delete file

`git mv  README.MD README ` move the file ,in other word file was renamed

`git log `   	check the commit history  : -p show differences among all commits

​						--stat  

`git` `commit` `--amend`  commit after last , two commits become the one 

`git reset`	unstaged file

`git checkout -- README.md` discard changes

`git  remote `  check remote repository   

`git remote add  newrepo http---`   add new repository

`git fetch remote-name ` 

`git push origin master`	

`git remote show orgin`  `git remote rename pb paul`

`git tag ` show the tags

`git tag -a v1.0 -m "version 1.0"`

`git tag v1.1`	 		  light tag

`git tag -d v1.0` 		delete tag

`git config --global alias.unstage 'reset HEAD--' ` alias

`git confi --global alias.last 'log -1 HEAD'`  

`git branch` 	create branch for your commit

`git branch testing `   create the testing branch 

​	`git  checkout testing ` switch to testing 

`git checkout -b iss53` create branch iss53,then switch to that branch

​      =`git branch iss53`   + `git checkout iss53`

`git fetch orgin ` 		update the local repository

`git push (remote) (branch)` push to remote branch 

`git checkout experiment ` 

`git  rebase master ` 	use the master as base ,apply experiment branch to it .

​				=  `git merge experiment`

 `git rebase master ` rebsase





testing

testing

Git 保证数据的完整性 -数据存储前计算校验和，然后以校验和来引用。计算机制是 SHA-1散列。

三种状态：已修改 modified ；已暂存 staged ；已提交 committed。

大致对应：工作目录   		；暂存区域（文件） ；Git仓库

初次运行前需要一些基础的配置。配置文件是config文件，有三个级别，直接列出配置项：git config --list 





