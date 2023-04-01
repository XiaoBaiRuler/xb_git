# 1. 常用git命令

## 1. 添加文件到缓冲区

```shell
    # 添加文件到缓冲区
    git add [file1] [file2]
    # 添加目录到缓冲区
    git add [dir]
    # 添加当前目录的所有进入缓冲区
    git add . 
```

## 2. 查看git状态

```shell
    # 查看当前git仓库状态
    git status
```

## 3. 查看git配置信息

```shell
    # 查看global的配置信息
    git config --global  --list
```

## 4. 提交代码命令

```shell
    # 提交所有代码，并且添加描述
    git commit -a -m [description]
```

## 5. 推送代码

```shell
    # 推送当前提交的代码到远程仓库
    git push
```

## 6. 拉取代码

```shell
    # 拉取远程代码到本地
    git pull
```
