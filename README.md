# 🛩️ 低空空域管理三维可视化平台

基于 **Cesium.js** 的低空经济三维可视化 Demo，模拟城市低空空域管理场景，展示无人机实时监控、空域分区、飞行航线等核心功能。

![项目截图](https://github.com/yj2002jx/low-altitude-airspace-cesium/raw/main/screenshot.png)

---

## ✨ 功能特性

| 功能 | 说明 |
|---|---|
| 🏙️ **三维城市场景** | 模拟三维建筑，立体视角展示城市低空环境 |
| 🚫 **空域分区可视化** | 红色禁飞区、黄色限飞区，按高度分层展示 |
| 🛩️ **无人机实时监控** | 4架不同类型无人机（巡检/配送/测绘/救援），自动沿航线往返飞行 |
| 🛤️ **飞行航线展示** | 虚线轨迹显示无人机飞行路径与航线 |
| 🎛️ **图层控制开关** | 可单独开关空域、建筑、无人机、轨迹图层 |
| 🗺️ **多底图切换** | 天地图影像、天地图矢量、OSM 三种底图一键切换 |
| 📍 **空间分析** | 点击地图任意位置，绘制500m安全缓冲区 |
| 📊 **实时状态面板** | 右侧面板实时显示无人机高度、速度、运行状态 |

---

## 🛠️ 技术栈

- **Cesium.js** — 三维地球引擎
- **原生 JavaScript** — 无框架依赖
- **HTML + CSS** — 界面布局
- **天地图 API** — 中文底图服务
- **GitHub Pages** — 在线部署

---

## 🌐 在线演示

👉 **[点击访问 Demo](https://yj2002jx.github.io/low-altitude-airspace-cesium/)**

---

## 📁 项目结构
low-altitude-airspace-cesium/
├── index.html    # 主页面（包含所有功能代码）
├── screenshot.png # 项目截图
└── README.md     # 项目说明文档


---

## 🚀 本地运行

```bash
# 1. 克隆仓库
git clone https://github.com/yj2002jx/low-altitude-airspace-cesium.git

# 2. 进入文件夹
cd low-altitude-airspace-cesium

# 3. 用浏览器直接打开 index.html
# 或用 VS Code Live Server 插件打开



