git init - Powers your folder to be managed by git  and initialises a new empty repository. 
It also create a .git folder that has all the revalant logic to manage versions of your project

2. 'Working Area' - There can be a bunch of files that are not currently handled by git.
It means that changes done or to be done in those files are not managed bt git yet .A file 
which is in working area is considered to be not in the staging area . when we do 'git status'
and we see a bunch of 'untracked files' then there are actual called to be in the working area

3.'Staging area' - what are the files are going to be next part of versionsthat we will create 
This staging are is the place where git knows that changes will be done from the last versions to
the next version.

4. 'repository Area'- This area actually contains details of all your previous registered versiona
and the files in this area .git already manages them and knows their version history 

5.'git add <file>' - moves files from working area to staging are 

6.'git rm --cached <file>'- moves file back from staging area to working area

7.'commit' - commit is the particulary version of the project . it cpatures the shapshot of the project 
staged changes and create a version out of it.

8.'git commit --m ""' -registers staging changes to a commmit

9.'git log' -list down all the commits of the repository.if you want to exit from git log press 'q'

10 .'git restore <file> -it removes all files changes from the staging area to be committed.This 
can be useful , if we did some dirty piece of code and now no more want it.instead of deleting any 
change line by line .we can restore it or you can say restore last clean version of the file .

11.'git restore --staged <file> -it removes file from changes from staging are to working area.
this only works if changes are in your staging area


