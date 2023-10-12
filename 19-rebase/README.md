```bash
(master) git pull 
(master) git checkout 1-branch 
(1-branch) git commit -m "test1" 
(1-branch) git checkout master 
(master) git pull 
(master) git checkout 1-branch
(1-branch) git rebase master 
(1-branch) git checkout master 
(master) git rebase 1-branch 
(master) git push 
```
