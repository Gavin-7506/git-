# Git的使用

## 一.  初始化git仓库

### 1. 基本信息设置

```bash
设置用户名
$ git config --global user.name 'Gavin-7506'
设置用户名邮箱
$ git config --global user.email '571051382@qq.com'
验证用
$ git config --list
```

### 2. 创建文件夹

```bash
$ mkdir test  (创建一个叫test的文件夹)
$ cd test     (进入文件夹)
$ pwd		  (显示当前目录)
$ ls		  (当前文件)
```

### 3. 初始化一个git仓库

```bash
$ git init
```

### 4. 创建一个文件

```bash
$ touch a1.php 
```

### 5. 查看仓库当前状态, 显示有变更的文件

```bash
$ git status
```

### 6. 添加到暂存区

```bash
$ git add a1.php
```

### 7. 将文件提交到仓库

```bash
$ git commit -m 'add a1.php'  (提交文件)
```

### 8. 修改仓库文件

```bash
$ vi a1.php
```

也可以在编辑器中修改 然后 **git status** 查看

### 9. 删除文件

```bash
$ rm a1.php  (删除文件)
$ git rm a1.php (从git中删除文件)
$ git commit -m '提交描述' (提交)
```



# Git的远程操作

## 二. git远程仓库

添加到远程仓库

```bash
$ git push  
```

### 2. 克隆操作

```bash
$ git clone https://github.com/Gavin-7506/test.git
```


