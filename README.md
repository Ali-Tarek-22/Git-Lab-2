# How to delete a branch?
## To delete a local branch:
git branch -d branch_name

## To delete a remote branch 
git push origin :branch_name


# How to checkout from a branch without commit?
You have to either stash then pop when you come back, or just commit before you checkout.

# How to list tags?
## To list all tags:  
git tag

# How to delete tags globally and locally
## To delete remote tag:
git push origin --delete tag_name
**or:**
git push origin :tag_name

## To delete local tag:
git tag -d tag_name
