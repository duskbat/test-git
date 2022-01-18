# git rebase
1.`git rebase -i "499febc9"` 要注意，rebase选取的位置是基部commit  
2. vim 编辑操作 pick ==> edit  
3. `git rebase --abort` 随时取消  
4. `git rebase --edit-todo` 重新打开vim  
5. `git commit --amend --author="weiye Mu<muwy1995@outlook.com>" --no-edit` 修改信息  
6. `git rebase --continue` 完成rebase  
