# Read me

-   建立分支 git branch `<name>`
-   建立並切換分支 git checkout -b `<name>`
-   查看所有分支(及目前所在分支) git branch
-   刪除分支 git branch -d `<name>`
-   刪除遠端分支 git push origin :`<name>`
-   合併並刪除 git merge --no-ff source-branch ; git branch -d source-branch
-   清掉 remote 不存在的 local branch : git remote prune origin
-   保留分支合併的紀錄 --no-ff git merge `<name>`
- 暫存 git stash

#### note

-   -d will only remove merged branches while -D will also remove unmerged branches, so -d will ensure that the branch is merged and you don't delete a branch by accident

#### VIM

-   :wq 確認並退出
-   :q 退出編輯器
