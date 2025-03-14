# 豆瓣广播备份工具

一个用于备份豆瓣个人广播的脚本，可以将广播内容导出为 Markdown 格式。

## 功能特点

- 支持备份单页或多页广播内容
- 支持导出为 Markdown 格式
- 支持备份广播的评论和互动数据
- 支持备份图片、链接和推荐内容
- 支持备份转发内容
- 支持自定义备份页码范围
- 支持断点续传
- 支持取消备份
- 支持进度显示

## 使用方法

1. 安装 Tampermonkey 浏览器插件
2. 点击 [这里](https://greasyfork.org/en/scripts/529789-%E8%B1%86%E7%93%A3%E5%B9%BF%E6%92%AD%E5%A4%87%E4%BB%BD%E5%B7%A5%E5%85%B7) 安装脚本
3. 访问你的豆瓣广播页面 https://www.douban.com/people/{你的豆瓣id}/statuses （豆瓣ID就是你主页的最后一串数字）
4. 点击"备份当前页面广播"或"备份多页广播"按钮
5. 选择要备份的页码范围（如果选择多页备份）
6. 等待备份完成，文件会自动下载

## 备份内容

- 广播发布时间
- 广播内容
- 图片（如果有）
- 评论和互动数据
- 转发内容（如果有）
- 推荐内容（如果有）
- 原始链接

## 注意事项

- 请合理设置备份页码范围，避免一次性备份过多页面
- 备份过程中请勿关闭页面
- 如果遇到网络问题，可以取消备份后重新开始
- 建议定期备份，以防数据丢失

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进这个项目。

## 许可证

MIT License

## 作者

Pieck

## 致谢

感谢 [DouBanExport](https://github.com/UlyC/DouBanExport) 项目的启发。 

# 豆瓣书影音内容备份

参考 [链接](https://ulyc.github.io/2022/02/11/Douban-Escape-Plan/)

安装 [此脚本](https://greasyfork.org/en/scripts/439867-%E8%B1%86%E7%93%A3%E8%AF%BB%E4%B9%A6-%E7%94%B5%E5%BD%B1-%E9%9F%B3%E4%B9%90-%E6%B8%B8%E6%88%8F-%E8%88%9E%E5%8F%B0%E5%89%A7%E5%AF%BC%E5%87%BA%E5%B7%A5%E5%85%B7)

后打开对应页面即可备份导出csv

豆瓣ID就是你主页的最后一串数字

豆瓣电影主页

https://movie.douban.com/people/{你的豆瓣id}

豆瓣读书主页

https://book.douban.com/people/{你的豆瓣id}

豆瓣音乐主页

https://music.douban.com/people/{你的豆瓣id}