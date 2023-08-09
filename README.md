# git 指令

Git|動作
-|-
git status|查看狀態
git add (file)|新增檔案
git add .|新增所有



### 遠端
`$ git remote add origin <your url>`

### 查看遠端

`$ git remote -v`
- origin  https://github.com/__.git (fetch)
- origin  https://github.com/__.git (push)

### 錯誤訊息
error: src refspec cyj does not match any

### 新增Branch(解決方法)
`$ git checkout -b BranchName`
- Switched to a new branch 'BranchName'

`git push origin BranchName`

#### 完成!!

---

### 下載特定分支(Branch)

`$ git clone -b branchName https://github.com/__.git`

```shell=
Cloning into 'All_about_me'...
remote: Enumerating objects: 27, done.
remote: Counting objects: 100% (27/27), done.
remote: Compressing objects: 100% (17/17), done.
remote: Total 27 (delta 3), reused 27 (delta 3), pack-reused 0
Receiving objects: 100% (27/27), done.
Resolving deltas: 100% (3/3), done.
```
