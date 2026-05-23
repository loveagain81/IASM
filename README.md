# IASM: 解释权转移模型 (Interpretive Authority Shift Model)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.20347318.svg)](https://doi.org/10.5281/zenodo.20347318)

**版本:** v0.1 (冻结核心模型)  
**作者:** Chun Wen  

## 简介
IASM（Interpretive Authority Shift Model）是一个用于分析短文本结构的解释模型。它将看似感性的文本（如三行情书、创伤叙事）抽象为一套极其精密的系统级事件：描述文本如何通过“局部语义断裂（SD）”与“高阶概念系统介入（HOCS）”完成意义重构或残差保留。

简单来说：**浪漫的本质，是高阶系统为了你修改了底层规则；而绝望的本质，是系统完美运转，却唯独将你隔离在逻辑的废墟中。**

## 核心文件导航
本项目包含完整的学术规范文档与案例库，建议按以下顺序阅读：

*   📖 **[full_spec.md](./full_spec.md):** IASM v0.1 完整规范（强烈建议首先阅读，包含核心定义、变量模型与系统状态划分）
*   🔍 **[cases.md](./cases.md):** 核心案例分析库（正向吸收型与反向残差型的标准拆解）
*   🗺️ **[roadmap.md](./roadmap.md):** 接口扩展方向与 v0.2 演进路线图

## 极简运行机制
模型将短文本运作机制抽象为：
**LSS（低阶解释权主导） ──→ SD（低阶解释权失效） ──→ HOCS介入（完成解释权上移） ──→ 解释重写 / 或残差保留**

根据 $C$（高阶吸收力）与 $D$（断裂强度）的博弈，系统坍缩为两种稳定态：
1.  **吸收型 (Closure System):** 断裂被强行闭合（通常生成“浪漫/升华”体验）。
2.  **非吸收型 (Residual System):** 断裂原貌保留，形成系统残差（通常生成“致郁/无解”的坍塌感）。

## 引用与开源协议
本理论框架遵循 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)（署名-非商业性使用）协议开源。
*   **建议引用格式:** Chun Wen. (2026). *IASM: Interpretive Authority Shift Model v0.1*. GitHub Repository. [当前仓库链接]
