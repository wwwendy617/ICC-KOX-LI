# 大众中国 KOX × 理想案例 · 演示页

根目录 `index.html` 即完整演示页；图片在 `assets/`。

**对外公开版（本仓库 `main`）** P08 仅保留 **KOS 弹窗**（文字与 FACT 卡片）；已移除 **组织架构**、**OKR** 两个弹窗及 KOS 弹窗内的 **数据快照图**（`assets/理想24年KOS数据快照.png` 已从仓库删除）。

**对内完整版**：本机 `_internal/` 目录（已 `.gitignore`，不会推送到 GitHub）中有 `index-full.html` + 快照图备份，参见其中 `README.txt`。

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
