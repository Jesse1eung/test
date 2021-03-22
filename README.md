git branch --set-upstream-to=origin/remote_branch  your_branch
git branch -u origin/remote_branch your_branch

本地删除远程test仓库ma分支：
git push test -d ma

删除上游设定:
git br --unset-upstream
上传到指定分支:
git push test ma:main
