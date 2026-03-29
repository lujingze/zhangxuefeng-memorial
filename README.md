# 张雪峰纪念合集

这个仓库现在拆成两部分：

- 公开版：索引链接与人物传记
- 私有版：公开网页的本地快照与下载清单

初始整理日期：2026-03-29

## 目标

- 收录张雪峰老师的公开账号、代表视频、已出版图书、重要采访与报道
- 为每条内容保留原始链接、发布时间、平台、主题、核验状态
- 做成一个可以持续补充的纪念索引库，而不是一次性文档

## 版权与发布边界

这个仓库默认采用“索引式纪念库”方案：

- 可以放：标题、链接、发布时间、平台、封面截图、简短摘要、公开资料来源
- 不建议直接放：整本电子书、整段搬运视频、批量下载的受版权保护内容
- 如果你后续拿到了授权，或者内容本来就是你自己保存的原创/合法备份，再单独扩展媒体库

这样做更适合放在 GitHub，也更不容易因为版权或平台规则被处理。

## 当前结构

- `public/`：准备公开发布的内容
- `private/`：只供本地留存的抓取内容
- `data/accounts.csv`：官方/团队账号索引
- `data/books.csv`：已出版图书索引
- `data/videos.csv`：代表视频索引
- `data/timeline.csv`：人物与作品时间线
- `data/press_and_sources.csv`：重要报道与来源索引
- `docs/精选内容.md`：可直接浏览的代表内容入口
- `docs/收录原则.md`：收录标准与后续补录建议
- `docs/发布建议.md`：GitHub / 静态站 / 其他平台发布建议

## 已收录内容

- 账号：5 条
- 图书：7 条
- 视频：12 条
- 时间线：8 条
- 报道与来源：8 条

## 公开入口

- [`public/README.md`](./public/README.md)
- [`public/索引链接.md`](./public/索引链接.md)
- [`public/人物传记.md`](./public/人物传记.md)

## 私有入口

- [`private/README.md`](./private/README.md)
- [`private/download_manifest.tsv`](./private/download_manifest.tsv)
- [`private/download_public_pages.sh`](./private/download_public_pages.sh)

## 建议下一步

1. 继续补齐“经典短视频”和“直播切片”的直接链接
2. 为公开视频和图书补封面截图
3. 用私有版继续积累网页快照与资料备份
4. 如果准备上线公开页面，可再加一个 GitHub Pages 静态首页
