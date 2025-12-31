# 🎓 LaTeX 课程设计/论文通用模板

这是一个基于 `ctex` 的通用学术报告/论文 LaTeX 模板，专为 **Overleaf** 和 **本地 XeLaTeX** 环境设计。

它采用了**模块化**的文件结构，将排版逻辑（`setup.tex`）与内容（`chapters/`）分离，让写作变得更专注于内容本身。

本模板大量的使用了 Gemini 3 辅助生成。

---

## 🚀 快速开始

### 方式 1：Overleaf 一键导入（推荐）

点击下方按钮，直接在 Overleaf 中打开本项目：

[![Open in Overleaf](https://img.shields.io/badge/Overleaf-Open%20in%20Overleaf-47a141?style=flat&logo=overleaf)](https://www.overleaf.com/docs?snip_uri=https://github.com/qwedc001/latex-report-template/archive/refs/heads/main.zip)

> **注意**：导入后，请务必将 Overleaf 的编译器设置为 **XeLaTeX**（Menu -> Compiler -> XeLaTeX）。

### 方式 2：本地使用

1. Clone 本仓库：
   ```bash
   git clone [https://github.com/](https://github.com/)<你的GitHub用户名>/<你的仓库名>.git

   ```

```

2. 确保你的 TeX 发行版（TeX Live / MacTeX）已安装，并支持 `ctex` 宏包。
3. 使用 `XeLaTeX` 编译 `main.tex`。

---

## ⚠️ 常见问题

**Q: 为什么编译报错 "Font ... not found"？**
A: 本模板使用了 `fontspec` 和中文字体配置，必须使用 **XeLaTeX** 编译器。在 Overleaf 左上角 Menu 中修改 Compiler 选项即可。

**Q: 目录里的点点不显示？**
A: 请重新编译一次（Recompile），LaTeX 通常需要编译两次才能正确生成目录和页码。

---

## 📜 License

CC BY-NC-SA
```
