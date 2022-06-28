# Read me

-   建立分支 git branch `<name>`
-   建立並切換分支 git checkout -b `<name>`
-   查看所有分支(及目前所在分支) git branch
-   刪除分支 git branch -d `<name>`
-   刪除遠端分支 git push origin :`<name>`
-   合併並刪除 git merge source-branch && git branch -d source-branch

#### note

-   -d will only remove merged branches while -D will also remove unmerged branches, so -d will ensure that the branch is merged and you don't delete a branch by accident
