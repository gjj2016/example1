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
<<<<<<< HEAD
Create a branch: git branch <branch-name>;
Change to another branch: git checkout <branch-name>;
Create and change branch: git checkout -b <branch-name>;
=======
Clone a remote repository to local repository: git clone git@github.com:/gjj2016/examples2;(use SSH protocal)
                   or    git clone https://github.com/gjj2016/examples2.git;(use Https protocal,need username and paaaword)

>>>>>>> feature1
