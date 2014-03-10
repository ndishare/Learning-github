## 创建主页

### 创建个人主页

1. 创建 repo: [user-id].github.io
2. 添加 index.html
3. git push origin master

### 创建项目主页

1. git symbolic-ref HEAD refs/heads/gh-pages
2. rm .git/index
3. 添加 index.html
4. git commit -m ""
5. git push origin master
    
> **Tip:** 使用专有域名，在 master 分枝或 gh-pages 根目录添加一个 CNAME 文件

