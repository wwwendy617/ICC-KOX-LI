# 大众中国 KOX × 理想案例 · 演示页

静态站点：`index.html` → `presentation.html`。图片在 `assets/`。

## GitHub + Render

1. 在 GitHub 新建空仓库（不要勾选初始化 README）。
2. 在本目录执行：
   ```bash
   git init -b main
   git add -A
   git commit -m "Initial: KOX deck"
   git remote add origin git@github.com:<你的账号>/<新仓库名>.git
   git push -u origin main
   ```
3. Render：选 **Static Site**，Root 填仓库根目录，Build 留空，Publish 目录留空或 `.`。

与 `TEST-Social` 大仓无关，可单独部署。
