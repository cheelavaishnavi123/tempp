You cloned from a different remote, want to push to new one. Configure. – 3M
git remote set-url origin https://github.com/username/repo.git

. Delete branch patient from remote repo. – 2M
git push origin --delete patient

Apply a .patch file from teammate and include in history. – 3M
git apply file.patch
git add .
git commit -m "Applied patch from teammate"

If you want last 3 commits:

git format-patch -3 HEAD


 If you want commits from a specific commit to now:

git format-patch <commit_id>