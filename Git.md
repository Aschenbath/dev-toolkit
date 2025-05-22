# Git

### 1.命令行的使用

## 完整上传项目的流程

​	

#### 1. git init                                   

初始化 Git 仓库

#### 2. git add .                                   

添加所有文件到暂存区



3. #### git commit -m "notes"     

做提交备注



#### 4. git remote add origin <address of the repositories>      

添加远程仓库



#### 5. git branch -M main                           

设置主分支为 main（GitHub 默认 main）



#### 6. git push -u origin main                  

​     # 推送到远程仓库



```bash
# 进入你本地的项目文件夹
cd /f/你的项目路径

# 初始化 git 仓库（本地第一次用）
git init

# 添加所有文件（你也可以选择指定文件）
git add .

# 创建第一次提交
git commit -m "Initial commit"

# 关联远程仓库
git remote add origin https://github.com/Aschenbath/mynotes.git

# 推送到 GitHub（首次需要 -u 设定默认上游分支）
git push -u origin main
```



## 指令详解

#### 1. git  log	

​	查看历史提交记录



#### 2. git  init

​	创建一个本地仓库

#### 3. git  add

​	  unstaged未暂存 -->修改文件

​	/untracked未跟踪-->新文件

​	工作区-->暂存区

###### 	git add . 

###### :把当前目录下 **所有被修改过的文件（包括新增和删除）**，添加到 Git 的“暂存区.

#### 4. git commit

​	缓存区-->仓库区