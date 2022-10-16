#rewriting-git-history

In this problem we have first clone the git repository, after cloning we have to create a local repository.

#commands to rewrtite the git history

git clone "http-url of repo"
git init
git add . -> to track all 
git commit -m "committed message"
git remote add origin "http repo url"
git push -u origin main

#to remove sensitive data
 git filter-branch --force --index-filter "git rm --cached --ignore-unmatch DOC-NAME" --prune-empty --tag-name-filter cat -- --all
 
 
