# Data

`species.json` 是完整数据集，每条一个物种。样例见 `sample.json`。

| 文件 | 内容 | 许可 |
|---|---|---|
| `species.json` | 除图鉴文字外的全部字段 | 编纂部分 MIT；第三方字段沿用各自条款（见 NOTICE.md） |
| `sample.json` | 占坑样例（字段结构演示，待逐项核对） | MIT |

## species.json 字段

| 字段 | 含义 | 来源 | 覆盖 |
|---|---|---|---|
| `id` | `Genus_species`，文件命名稳定键 | — | 全部 |
| `scientificName` / `authority` | 学名与命名人 | POWO/WCVP | 全部 |
| `taxonomy` | 分类体系、目/科/属 | POWO/WCVP | 全部 |
| `names` | 按语言代码的俗名（en / zh-Hans / zh-Hant / ja …） | POWO / GBIF / 中国植物志 | 待核对 |
| `ids` | wikidata / gbif / powo / inaturalist 跨库 ID | 各库 | 待核对 |
| `range` | 分布、生境 | POWO / GBIF | 待核对 |
| `traits` | 株高、花期、习性等 | POWO / 中国植物志 | 待核对 |
| `conservation` | IUCN 等级、CITES 附录 | IUCN / Wikidata | 待核对 |
| `sticker` | 文件、类型、评分、是否过质量线、许可、参考图来源 | 本项目 | 全部（占坑阶段为 pending） |

## 数据源 / Sources

- WCVP / POWO <https://powo.science.kew.org>（CC BY 3.0）
- GBIF <https://www.gbif.org>
- 中国植物志 / Flora of China
- IUCN Red List <https://www.iucnredlist.org>
