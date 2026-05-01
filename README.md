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

```bash
# 使用 Node.js 的 npx serve
npx serve .

# 或使用 Python 3
python3 -m http.server 8000
```

然后访问 `http://localhost:8000`。

Then visit `http://localhost:8000`.

---

## 🎮 游戏规则 / Game Rules

1. 三队各派一人上场，**不能看大屏幕**
2. 大屏幕随机抽取任务动作，队友用 **YES / NO** 引导（靠近目标 = YES，远离目标 = NO）
3. 完成动作用时最短的队伍获胜，分别获得 **3 / 2 / 1** 积分

---

## 🎯 动作列表 / Action List

| # | 动作 |
|---|------|
| 1 | 单膝跪地和新郎击掌 |
| 2 | 和新郎击掌一次 |
| 3 | 亲一下喜糖盒 |
| 4 | 把蜡烛顶在自己头上 |
| 5 | 向新郎鞠躬90度 |
| 6 | 拿起杯子喝一口 |
| 7 | 用左手和新郎握手 |
| 8 | 把一条餐巾纸披在头上 |
| 9 | 找一个人拥抱 |
| 10 | 一条腿站到椅子上 |
| 11 | 找到新娘的手捧花并举起来 |
| 12 | 男生拥抱新郎，女生拥抱新娘 |
| 13 | 倒着走三步 |
| 14 | 把桌上的蜡烛藏在衣服里 |
| 15 | 单脚站立保持5秒 |

---

## ✨ 功能特性 / Features

- 粉色婚礼主题 UI / Pink wedding theme UI
- 三队记分板，支持两轮积分累计 / Three-team scoreboard with two-round score accumulation
- 随机滚动抽取任务动作（手动停止）/ Random scrolling action picker (manual stop)
- 计时器（停止后自动记录到选中队伍）/ Timer (auto-records to selected team after stop)
- 队伍名称可双击编辑 / Team names editable by double-click
- 自适应文字大小 / Auto-fitting text size
- 全屏规则展示 / Full-screen rules display
- 键盘快捷键 / Keyboard shortcuts：
  - 空格 (Space) = 计时器开始/停止
  - R = 抽取/停止
  - 1/2/3 = 选择队伍

---

## 🛠 技术栈 / Tech Stack

- HTML5
- CSS3（含动画 / with animations）
- Vanilla JavaScript

无需任何依赖或构建工具。No dependencies or build tools required.

---

## 📄 License

MIT