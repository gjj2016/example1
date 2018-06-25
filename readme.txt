Git is a dictribute version control system;
Git is free.
Git is very useful, and easy to learn.
Git is study from charmy's blog.
Git init and Git add, Git commit, Git log, Git status, Git reset, Git reflog
Git is A;
Git is B;
Some new git commond: git checkout -- <file>, git reset HEAD <file>;
Connect a local repository with remote repository: git remote add origin git@github.com gjj2016/example1.git;
Push local repository to remote repository: git push -u origin master; (first push, other push without parameter '-u');
Create a branch: git branch <branch-name>;
Change to another branch: git checkout <branch-name>;
Create and change branch: git checkout -b <branch-name>;
Clone a remote repository to local repository: git clone git@github.com:/gjj2016/examples2;(use SSH protocal)
                   or    git clone https://github.com/gjj2016/examples2.git;(use Https protocal,need username and paaaword)
Delete a branch: git branch -d <branch-name>;
Merge a branch: git merge <branch-name>;
Once merge conflict, we have to manually edit the conflict file, then commit.

List branch merge graph: git log --graph --pretty=oneline --abbrev-commit;

Use paremeter '--no--ff' when merge can merge without Fast Forward, and can keep merge history in branch merge graph;

Merge bug branch when we work on dev branch, and we don't want to commit changes in dev branch, now we can use git stash to save our work on dev branch and clear stage workspace. After we have solve the bug branch, we can switch to dev branch, and use git stash apply to recover our work on dev branch, then use git stash drop to delete the stash workspace. Or use git stash pop to recover and drop, when we have many items in stash workspace, we can use git stash list to list all items in stash workspace, and use git stash apply stash@{i} to recover the (i+1)'s item in stash workspace.
