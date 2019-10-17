# offduty.github.io

首先使用 Hugo 本地生成静态网页文件，存储在 `public` 文件夹下，然后上传 public 中的内容至 Github page，间接实现博客展示的功能。

**用法**
```shell
# 1. 在本地修改或新增 md 文件；
# 2. 本地编译：
$ hugo --theme="maupassant" --buildDrafts --baseURL="https://offduty.github.io"
# 3. 进入 public 目录：
$ cd public
# 4. 推送到 github 
$ git add .
$ git commit -m "first commit"
$ git push -u origin master
```
输入 github 用户名和密码。待上传完成。打开 https://offduty.github.io， 即可看到效果。
