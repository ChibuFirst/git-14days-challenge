# Screenshots of Git GUI Usage
![Add](https://user-images.githubusercontent.com/52785343/86520332-02f24080-be3b-11ea-8fb2-c21e3ce0406c.PNG)
![Commit](https://user-images.githubusercontent.com/52785343/86520335-0be31200-be3b-11ea-9758-6dcbf241f082.PNG)
![Committed](https://user-images.githubusercontent.com/52785343/86520336-0ede0280-be3b-11ea-8918-f831b51404e7.PNG)
![Push](https://user-images.githubusercontent.com/52785343/86520346-130a2000-be3b-11ea-9840-51af508473ec.PNG)
![Push success](https://user-images.githubusercontent.com/52785343/86520348-156c7a00-be3b-11ea-8384-3e494ff6996b.PNG)

# Demo text
### Some Git Commands, Their Meaning and Examples

Commands | Usages 
-- | --
git config | This command sets the author name and email address respectively to be used with your commits. Eg: `git config –global user.name “[name]”`
git init | This command is used to start a new repository. Eg: `git init [repository name]`
git clone | This command is used to obtain a repository from an existing URL. Eg: `git clone [url]`
git add | This command adds a file to the staging area. Eg: `git add [file]`
git commit | This command records or snapshots the file permanently in the version history. Eg: `git commit -m “[ Type in the commit message]”`
git diff | This command shows the file differences which are not yet staged. Eg: `git diff`
git reset | This command unstages the file, but it preserves the file contents. Eg: `git reset [file]`
git status | This command lists all the files that have to be committed. Eg: `git status`
git rm | This command deletes the file from your working directory and stages the deletion. Eg: `git rm [file]`
git log | This command is used to list the version history for the current branch. Eg: `git log`
git show | This command shows the metadata and content changes of the specified commit. Eg: `git show [commit]`
git tag | This command is used to give tags to the specified commit. Eg: `git tag [commitID]`
git branch | This command lists all the local branches in the current repository. Eg: `git branch`
git checkout | This command is used to switch from one branch to another. Eg: `git checkout [branch name]`
git merge | This command merges the specified branch’s history into the current branch. Eg: `git merge [branch name]`
git remote | This command is used to connect your local repository to the remote server. Eg: `git remote add [variable name] [Remote Server Link]`
git push | This command sends the committed changes of master branch to your remote repository. Eg: `git push [variable name] master`
git pull | This command fetches and merges changes on the remote server to your working directory. Eg: `git pull [Repository Link]`
git stash | This command temporarily stores all the modified tracked files. Eg: `git stash save`

> Source: [dzone article](https://dzone.com/articles/top-20-git-commands-with-examples)
