# 1.remove branches locally and remotely:
1- remove branches locally and remotely:
we can remove it locally by:
git branche -d dev
git branche -d dev
we can remove it remotely by:
git branch origin --delete test 
git branch origin --delete dev

# 2. tell me how to checkout another branch without commit changes
git stash 
git checkout branchName
git stash apply // if i decided i want the changes back, apply them on a new branch
git stash drop /// after applying you can remove stash


# 3. tell me how to delete tag locally and remotely
locally: git tag
git tag -d TagName

remotely:
git tag 
git push origin --delete v1.7

# 4. tell me how to list tags
git tag 
git tag -1 --sort=-vrefname



![Screenshot from 2024-06-30 14-16-48](https://github.com/shrouq32/lab2/assets/174201756/f6b1441d-7a12-4d10-89aa-f7eea1d35317)
