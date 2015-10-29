# repo_demo

ssh -T git@github.com
git config --list
git remote add origin git@github.com:cxlg/LKK.git
git clone git@github.com:cxlg/LKK.git
git add file1.ext
git commit -m "comment"
git push origin master

git checkout -b "cxlgb1"
git checkout master
git checkout cxlgb1

git diff <source_branch> <traget_branch>
git merge <branch>
git status

--get files from repo_demo repository's master branch
git pull repo_demo master
