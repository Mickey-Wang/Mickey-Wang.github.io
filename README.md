# new-blog

## 命令

- **hexo server**  启动本地服务
- **hexo g -d**  生成本地静态文件并部署
- **hexo clean** 清除缓存文件 (db.json) 和已生成的静态文件 (public)
- **hexo new [layout] <title>** 指定文章的布局（layout），默认为 post，可以通过修改 _config.yml 中的 default_layout 参数来指定默认布局
- **hexo publish [layout] <title>** 通过 publish 命令将草稿移动到 source/_posts 文件夹

## layout参数

Hexo 有三种默认布局：post、page 和 draft

- post: source/_posts
- page: source
- draft: source/_drafts
