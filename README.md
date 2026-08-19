# 每日每日

一个给温迪和贝蒂用的每日计划 / 记录 / 复盘小工具。单文件、纯静态，无需构建。

## 功能
- 时间轴（左「想做」/ 右「做了」），块可拖动、改时长、点开编辑
- 编辑块时可选：**拆成时间块** / **作为清单** / **整块**
- 全部成员并排，或只看某一人
- 四象限、今日规划
- 复盘教练（按框架一步步追问；接 API 时为量身追问，否则走预设阶梯）
- 导入 / 导出数据（JSON），方便跨设备搬运
- 可「添加到主屏幕」当 App 使用

数据保存在浏览器本地（localStorage），不上传服务器；换设备或清缓存请先用「导入 / 导出」备份。

## 部署

### Vercel（推荐）
1. 把本仓库 import 到 Vercel。
2. Framework Preset 选 **Other**（不要选任何需要 build 的框架）。
3. Build Command / Output 留空，直接 Deploy。

### GitHub Pages
Settings → Pages → Source: Deploy from a branch → `main` / `(root)` → Save。
几分钟后访问 `https://<用户名>.github.io/<仓库名>/`。

> 入口文件是 `index.html`，放在仓库根目录即可，无需其它配置。
