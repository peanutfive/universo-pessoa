# Universo Pessoa · 佩索阿宇宙

费尔南多·佩索阿（Fernando Pessoa, 1888–1935）异名者交互星图。

佩索阿一生创造了超过 72 个异名者——每个都拥有独立的传记、写作风格、哲学立场，甚至星盘。本项目将这个庞大的文学宇宙可视化为一张可交互的星座图。

**在线访问 →** [peanutfive.github.io/universo-pessoa](https://peanutfive.github.io/universo-pessoa/)

## 收录内容

| 类别 | 数量 | 代表人物 |
|------|------|----------|
| 正名 (Ortónimo) | 1 | Fernando Pessoa |
| 主要异名者 | 3 | Alberto Caeiro · Ricardo Reis · Álvaro de Campos |
| 半异名者 | 3 | Bernardo Soares · Barão de Teive · Vicente Guedes |
| 次要异名者 | 70+ | Alexander Search · Maria José · Chevalier de Pas 等 |

每位异名者包含：传记、写作风格、哲学/世界观、代表名句、主要作品列表、关系网络。

## 交互方式

- **拖拽** — 移动节点
- **滚轮** — 缩放视图
- **悬停** — 高亮关联节点与连线，淡化其余；显示隐藏的标签
- **点击** — 打开右侧详情面板（传记、作品、名句、关系）
- **面板内人名可点击** — 跳转到对应异名者
- **顶部筛选** — 按类型（主要 / 半 / 次要）或语言（葡 / 英 / 法）

## 视觉设计

星座隐喻的深空布局，径向同心环分层：

```
            ·  次要异名者（外环，按集群聚合）  ·
         ·    半异名者（中环）    ·
      ·  三大异名者（内环）  ·
           佩索阿（中心）
```

节点按集群自然聚合：《闲谈者》合作者群、童年异名者群、英语异名者群、侦探文学群、家族关系群等。

## 技术

单文件 HTML，零依赖构建。运行时加载：

- [D3.js v7](https://d3js.org/) — 力导向图 + SVG 渲染
- [Google Fonts](https://fonts.google.com/) — Cormorant Garamond + Noto Serif SC

## 数据来源

- [Registry of Pseudonyms — Fernando Pessoa](https://www.registryofpseudonyms.com/fernando_pessoa.html)
- Richard Zenith, *Pessoa: A Biography* (2021)
- Casa Fernando Pessoa — [casafernandopessoa.pt](https://www.casafernandopessoa.pt/)
- Pessoa, *Carta a Adolfo Casais Monteiro*, 13 Jan 1935

## License

[MIT](./LICENSE)
