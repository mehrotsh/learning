**1) How to remove a big file wrongly committed**

git filter-branch --tree-filter 'rm -rf AWS/storage/.terraform/' HEAD

**2) gitignore document**

https://www.atlassian.com/git/tutorials/saving-changes/gitignore