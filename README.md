# 🌍 国际贸易实务 · 智能复习系统 (Int'l Trade Master)

> **拒绝死记硬背，让复习像“刷卡”游戏一样简单高效！** 🚀
> 专为《国际贸易实务》课程打造的沉浸式复习工具。集**核心考点记忆**、**强化应用练习**、**错题智能追踪**于一体，帮助学生轻松攻克 Incoterms、信用证、海运保险等难点。

[在线演示 (Demo)](https://www.google.com/search?q=%23) ---

## ✨ 核心亮点 (Features)

为什么选择这个复习工具？

### 🧠 1. 深度强化闭环 (Deep Learning Loop)

不同于普通的抽认卡，我们实现了**“一卡一题”**的深度关联：

* **记忆阶段**：翻转卡片，记忆核心概念（覆盖一级/二级重点）。
* **应用阶段**：每张卡片配备专属**强化练习题**。
* *计算卡片* ➡️ 自动匹配高难换汇成本/运费计算题。
* *概念卡片* ➡️ 匹配案例分析或逻辑辨析题。


* **反馈阶段**：做错即加入“错题本”，形成记忆闭环。

### 🔄 2. 三大智能模式

* **顺序刷卡**：系统化遍历所有知识点。
* **🎲 随机抽查**：模拟考试环境，打乱顺序检测真实水平。
* **🔥 错题重练**：智能筛选未掌握的卡片，哪里不会点哪里。

### 📊 3. 可视化学习报告

* 实时追踪复习进度和掌握率。
* 自动生成**高频错题榜** (Top Missed Concepts)。
* 支持 **一键导出 PDF 报告**，学习成果看得见！

### 💻 4. 极致轻量 & 零依赖

* **单文件架构**：只有一个 `.html` 文件，无需安装任何 App，无需配置服务器。
* **跨平台**：手机、平板、电脑浏览器点开即用。
* **专业体验**：包含封面引导、沉浸式翻转动画、退出机制。

---

## 📸 界面预览 (Screenshots)

| **沉浸封面** | **核心抽认卡** |
| --- | --- |
| <img src="[https://via.placeholder.com/300x500?text=Cover+Screen](https://www.google.com/search?q=https://via.placeholder.com/300x500%3Ftext%3DCover%2BScreen)" width="300" /> | <img src="[https://via.placeholder.com/300x500?text=Flashcard+Flip](https://www.google.com/search?q=https://via.placeholder.com/300x500%3Ftext%3DFlashcard%2BFlip)" width="300" /> |

| **强化练习弹窗** | **学习报告导出** |
| --- | --- |
| <img src="[https://via.placeholder.com/300x500?text=Quiz+Modal](https://www.google.com/search?q=https://via.placeholder.com/300x500%3Ftext%3DQuiz%2BModal)" width="300" /> | <img src="[https://via.placeholder.com/300x500?text=Report+PDF](https://www.google.com/search?q=https://via.placeholder.com/300x500%3Ftext%3DReport%2BPDF)" width="300" /> |

---

## 🚀 快速开始 (Quick Start)

你不需要懂代码，只需 3 步即可开始复习：

1. **下载**：点击右上角的 `Code` -> `Download ZIP`，或者直接下载仓库中的 `index.html` 文件。
2. **运行**：双击下载的 `.html` 文件，它会自动在你的浏览器（Chrome/Edge/Safari）中打开。
3. **开始**：点击“开始挑战”，享受复习过程！

---

## 🛠️ 自定义题库 (For Developers/Teachers)

如果你想替换成其他科目的题库，只需修改 HTML 文件底部的 `db` 数组即可。

```javascript
// 在 <script> 标签内找到 db 数组
const db = [
    {
        id: 1, 
        level: 1, // 1=核心重点, 2=次要重点
        chapter: "章节名称", 
        type: "calc", // calc=计算, case=案例, choice=选择
        front: "卡片正面问题", 
        back: "卡片背面答案", 
        quiz: { 
            q: "强化练习题目", 
            options: ["选项A", "选项B", "选项C", "选项D"], 
            ans: 1, // 正确答案的索引 (0代表A, 1代表B...)
            explain: "题目解析" 
        } 
    },
    // ... 添加更多数据
];

```

---

## 🤝 贡献 (Contributing)

欢迎提交 PR！如果你有更好的题目、更棒的 UI 设计或者发现了 Bug：

1. Fork 本仓库
2. 新建分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. Push 到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

---

## ⭐ Support

如果这个项目帮助你在期末考试中取得了**好成绩**，或者你觉得这个工具很有趣：

* 请给这个项目点一颗 **Star** ⭐️！
* 分享给你的同学或学生。

**Happy Learning!** 🎓

---

### 📝 TODO

* [ ] 增加夜间模式
* [ ] 支持 Excel/CSV 导入题库
* [ ] 增加更多 gamification 元素 (成就勋章)

---

**License**
Distributed under the MIT License. See `LICENSE` for more information.
