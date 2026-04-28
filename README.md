# 💍 Coco 婚礼挑战赛

🌐 **在线体验 / Live Demo:** [https://wenyang33.github.io/coco-celebration/](https://wenyang33.github.io/coco-celebration/)

一个婚礼派对游戏 Web App，适合投影到大屏幕上使用。

A wedding party game Web App, designed to be projected onto a big screen.

---

## 📦 安装与使用 / Installation & Usage

### 方法一：克隆仓库 / Clone the Repository

```bash
git clone https://github.com/wenyang33/coco-celebration.git
cd coco-celebration
```

然后直接在浏览器中打开 `index.html` 即可：

Then simply open `index.html` in your browser:

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### 方法二：使用本地服务器（可选）/ Use a Local Server (Optional)

如果你希望通过本地服务器运行，可以使用以下任一方式：

If you prefer to run it via a local server, use any of the following:

```bash
# 使用 Node.js 的 npx serve
npx serve .

# 或使用 Python 3
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`（或 `http://localhost:3000`，取决于工具）。

Then visit `http://localhost:8000` (or `http://localhost:3000`, depending on the tool).

### 方法三：直接下载 / Direct Download

1. 在 GitHub 页面点击绿色的 **Code** 按钮
2. 选择 **Download ZIP**
3. 解压后打开 `index.html`

1. Click the green **Code** button on the GitHub page
2. Select **Download ZIP**
3. Unzip and open `index.html`

---

## 🎮 游戏规则 / Game Rules

1. 三队各派一人上场，**不能看大屏幕**
2. 大屏幕随机抽取任务动作，队友用 **YES / NO** 引导（靠近目标 = YES，远离目标 = NO）
3. 完成动作用时最短的队伍获胜，分别获得 **3 / 2 / 1** 积分

---

## 🎯 动作列表（25个）/ Action List (25 Actions)

| # | 动作 |
|---|------|
| 1 | 把桌上的一把叉子插进院子的土里 |
| 2 | 单膝跪地和新郎击掌 |
| 3 | 把你的右脸贴在一扇窗户上 |
| 4 | 用屁股碰一下新娘的椅子 |
| 5 | 把一张贴纸贴到新郎背上 |
| 6 | 和新郎击掌三次 |
| 7 | 亲一下新娘手背 |
| 8 | 把桌上的一朵花夹在自己耳朵上 |
| 9 | 趴在地上做三个俯卧撑（或者类似动作） |
| 10 | 向新郎鞠躬90度 |
| 11 | 把一个杯子顶在自己头上 |
| 12 | 用左手和新郎握手，同时右脚抬起来 |
| 13 | 把一条餐巾纸披在头上像头纱一样 |
| 14 | 找到一个气球并坐爆它 |
| 15 | 和现场三个不同的人拥抱 |
| 16 | 把椅子搬到新郎旁边坐下 |
| 17 | 对着最近的镜子或手机摄像头摆pose |
| 18 | 把桌上的筷子叼在嘴里 |
| 19 | 找到新娘的手捧花并举起来 |
| 20 | 站到椅子上面向Coco打招呼 |
| 21 | 把两只手都放在新郎的肩膀上 |
| 22 | 倒退走路绕桌子一圈 |
| 23 | 用额头顶住墙壁保持5秒 |
| 24 | 把桌上的一个苹果（或东西）藏在衣服里 |
| 25 | 单脚站立保持10秒 |

---

## ✨ 功能特性 / Features

- 优雅婚礼主题 UI（紫色夜空 + 粉金色调）/ Elegant wedding theme UI (purple night sky + pink-gold tones)
- 三队记分板，支持两轮积分累计 / Three-team scoreboard with two-round score accumulation
- 随机滚动抽取任务动作（手动停止）/ Random scrolling action picker (manual stop)
- 计时器（停止后自动记录到选中队伍）/ Timer (auto-records to selected team after stop)
- 队伍名称可双击编辑 / Team names editable by double-click
- 全屏规则展示 / Full-screen rules display
- 键盘快捷键 / Keyboard shortcuts：空格=计时器 (Space=Timer)，R=抽取 (R=Draw)，1/2/3=选队 (1/2/3=Select Team)

---

## 🛠 技术栈 / Tech Stack

- HTML5
- CSS3（含动画 / with animations）
- Vanilla JavaScript

无需任何依赖或构建工具。No dependencies or build tools required.

---

## 📄 License

MIT