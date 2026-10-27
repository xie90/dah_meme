# dsh-memes

鲸鱼娘 / 大肥鱼表情包归档，共 **97** 张，3 个图库。
由 DSH 表情包目录 `~/.dsh/meme-packs` 导出，保留原始分类、描述与关键词。

**[在线画廊 gallery.html](gallery.html)** — 搜索 + 按库/情绪过滤（开 Pages 就能直接用）。

## 图库

| 图库 | ID | 数量 | 授权 | 链接 |
| --- | --- | --- | --- | --- |
| 我的收藏(升级不丢) | `dsh-meme-user` | 25 | 未声明 | [进入](packs/dsh-meme-user/README.md) |
| 泡泡表情包 | `paopao-whale-girl` | 27 | CC-BY-NC-SA-4.0 | [进入](packs/paopao-whale-girl/README.md) |
| 鲸鱼娘表情包 | `whale-girl-emoji` | 45 | noncommercial-fan | [进入](packs/whale-girl-emoji/README.md) |

## 目录结构

```
packs/<库ID>/manifest.json   # 库元信息
packs/<库ID>/README.md       # 带缩略图的清单
packs/<库ID>/memes/<分类>/<文件>
catalog.json                 # 全量索引：分类/描述/关键词/大小/sha256
gallery.html                 # 静态画廊页，直接读 catalog.json
```

## 用法

- 想装回 DSH：把 `packs/<库ID>/` 整个拷进 `~/.dsh/meme-packs/`，并在图库设置里启用。
- 想自己用：`memes/` 下按情绪分好了，直接拿。
- 索引字段说明：`tag` 情绪分类、`caption` 一句话描述、`keywords` 检索词。

## 授权

各图库授权不同，见上表与各库 README。`paopao-whale-girl` 为 CC-BY-NC-SA-4.0，
`whale-girl-emoji` 为仅限非商业的同人使用；转载或商用前请先看对应库的声明。
