### Hexo 常用命令
- hexo init 初始化（该命令只能做空目录执行，否则会报错。此时，可以将.git等文件夹剪切出去，完事后在拷贝回来。）
- hexo clean来清理一下public的内容，然后再来重新生成和发布
- hexo new "postName" #新建文章
- hexo new page "pageName" 新建页面
- hexo generate 生成静态页面至public目录
- hexo server 开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
- hexo deploy 部署到GitHub
- hexo help  查看帮助
- hexo version 查看Hexo的版本

- Hexo默认会把所有md文件都转换成html，包括README.md。因此，需要每次生成之后、上传之前，手动将README.md复制到public目录，并删除README.html