# plant-sticker · 植物贴纸库

植物贴纸库：每种一张白边贴纸，附多语言植物名与结构化数据。学 [花叔 huashu-bird-sticker](https://github.com/alchaincyf/huashu-bird-sticker) 的「鸣迹」模式。

> 🚧 **占坑阶段**：数据 schema、许可、样例数据已就位；贴纸尚未生成（筹备中）。全球维管植物约 35 万种，不能一步全做——**先划中国常见植物 / 观赏植物子集**，再逐步扩。

**English:** Stickers for the world's plant species. Vascular plants (~350k) can't be done all at once, so we start with a scoped subset (common / ornamental plants of China), then expand. **Early stage: schema, license and samples are live.**

---

## 这是什么

这是「**草木迹（Flora Tracks）**」iOS App 的贴纸库：每认出/收藏一种植物，就把它的贴纸贴进本子，盖日期地点邮戳。

## 灵感与方法

照抄花叔四步流水线（见他的[长文](https://x.com/AlchainHust/status/2116088319511605472)）：找参考图 → 照着画 → 独立打分审校 → 画不好就重画。参考图不打包，将逐种在 `data/species.json` 溯源。

## 数据 schema

见 [`data/sample.json`](data/sample.json) 与 [`data/README.md`](data/README.md)。

## 目录结构

```
stickers/<Order>/<Family>/<Genus_species>.webp
data/species.json（尚未生成）
data/species.schema.json
data/README.md
LICENSE.md
NOTICE.md
```

## 许可

- 贴纸：**PolyForm Shield 1.0.0** —— 源码/资源公开、可复制分发，但**不是 OSI 开源许可**，有**竞争限制**：禁止做与草木迹竞争的观察/识植物/植物图鉴产品。
- 数据（编纂部分）：**MIT**；第三方条款见 [NOTICE.md](NOTICE.md)。

详见 [LICENSE.md](LICENSE.md)。

## Roadmap

- [x] 数据 schema 与许可
- [ ] 首批植物贴纸小样（100–300 种）跑通流水线
- [ ] 中国常见/观赏植物子集
- [ ] 按地区/类群逐步扩
- [ ] 草木迹 iOS App 上架

## 数据源

- WCVP / POWO（Kew，分类权威，CC BY 3.0）
- GBIF（跨库 ID、分布）
- 中国植物志 / Flora of China（中文名与图鉴）
- IUCN Red List（保护等级）

## 贡献

发现贴纸错误、分类/植物名有误、或有更好的开放参考图，欢迎提 issue / PR。
