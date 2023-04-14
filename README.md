# hexo-theme-A4
模仿A4纸张的一个hexo极简主题。主打一个简洁。

## TODO

- [x] waline评论功能
- [x] a标签互动颜色改变
- [x] header加入头像
- [x] 首页的差异化，页面接近A4纸，相比于归档页面宽度更窄
- [x] 首页展示为自定义post页面(待配置化)
- [x] footer新增a标签（待配置化）
- [x] 归档页面自动年份分隔且统计该年文章数量（待自动化）
- [ ] 文章目录
- [ ] 归档页面搜索功能
- [ ] RSS

## 首页

![](/source/img/index.png)

## 归档

![](/source/img/archive.png)

## 评论

![](/source/img/comment.png)



## 配置

### 首页设置

大部分主题，包括原主题都采用瀑布流的方式展示主页。我想也应该有朋友会像我一样需要首页展示一些介绍信息。

你只需要做如下配置:

- hexo new post  xxx  或者 找到已有的xxx.md

- 在新建的xxx.md文件front-matter中添加：`index:true`

- 访问localhost:4000，即可展示xxx.md内容

  

你可以设置多个文件的front-matter中添加：`index:true`，内容都将显示到主页

### 评论模块配置

新增了waline评论

你只需要做如下配置:

- 在该主题配置文件_config中把comment相关信息启用
- 启用过后，默认所有新建post都开启comment
- 如果你想关闭某个post的comment，在对应post的font-matter中添加：`comment:false`即可


## 灵感来源：

https://github.com/zheli-design/hexo-theme-one-paper

原主题主打博客网站纯粹写作阅读体验，认可该设计理念。

我在原作基础上联想到调整为A4页面的设计，后续将会新增一些`必要功能`，页面进行微调。

## 支持

如果觉得我做的不错，请给我一个start。

