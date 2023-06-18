## **GIT COMMAND**
<img src="../_src/img/git_logo.png" style="width: auto;height: 100px" >
*Use these some command to use Git.*
1. Checking Git version:
    > git -v
2. Creating a new Git repo:
    > git init
3. Checking staging files:
    > git status
4. Adding files to staging environment:
    > git add [file's name].[file format]
    > git add --all
    > git add -A
    > git add *
    > git add .
5. Commiting all staged files:
    > git commit -m ["your message"]
    > git commit -am ["your message"]
6. Checking branch you owned:	
    > git branch
7. Creating a new branch's repo:
    > git branch -M [new branch's name]	
    > git branch [branch name]
8. Switching a branch's repo:
    > git checkout [your branch's name]
9. Changing a branch's repo name:
    > git branch -m [new branch's name]
10. Deleting a branch's repo:
    > git branch -d [branch's name]
11. Deleting a folder:
    > git rm -r [folder's name]
12. Checking the remote you owned:
    > git remote -vgit remote -v
13. Creating a GitHub's remote:
    > git remote add [remote's name] [remote url]
14. Changing a remote's name:
    > git remote rename [old remote's name] [new remote name]
15. Deleting a remote:
    > git remote remove [remote's name]
16. Showing remote's information:
    > git remote show [remote's name]
17. Changing remote's URL:
    > git remote set-url [remote's name] [remote url]
18. Uploading your repo to GitHub:
    > git push [remote's name] [branch's name]
19. Uploading your repo to GitHub (FORCE MODE!):
    > git push -f [remote's name] [branch's name]
20. Downloading your repository in GitHub:
    > git clone [your git url in github]
21. Merging a repo from another repo:
    > git merge [your another repo]