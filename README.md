# 江少的选品参谋（中东选品工具箱）

面向中东电商市场（Noon / Amazon.ae / SHEIN / Namshi / Trendyol / Fordeal / Ounass 等）的选品研究工具，内置 VAT 税费计算、定价测算、各平台佣金与参考信息。

## 特性
- 单文件静态 HTML，无需后端，打开即用
- 多销售市场 VAT 选项（UAE / 沙特 / 科威特等），含税 / 净价口径清晰
- 平台佣金、定价计算器一目了然

## 部署（GitHub Pages）
1. 将本仓库推送到你的 GitHub 仓库
2. 仓库 **Settings → Pages → Source** 选择 `main` 分支 `/ (root)`，保存
3. 访问 `https://<你的用户名>.github.io/<仓库名>/`

> 静态部署即可使用全部计算与参考功能。实时商品抓取需另接 ScraperAPI / Cloudflare Worker 等后端代理，不在本静态包范围内。
