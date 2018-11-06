Git is a version control system.
Git is free software.

mkdir filename
cd filename
pwd %current directory

git init
ls -ah

%put readme.txt into filename/its sub files
git add readme.txt
git add anotherfile
git commit -m <message>

git status
git diff readme.txt

git log --pretty=oneline

%past
git reset --hard HEAD^ % commit id
cat readme.txt

git reset --hard 476023e % or 476023e (commit id)
cat readme.txt

%future
git reflog  % to find the commit id

%modify.
