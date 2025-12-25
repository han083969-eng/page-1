# 🚀 高效制冷系统循环分析工具 (Cycle Analysis Tool)

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Field](https://img.shields.io/badge/Field-Energy_and_Power-orange)

> **项目定位**：基于 Python 的高效热力学性质查询与循环效率计算工具。

---

## 📊 核心公式与物理模型
本项目核心计算基于热力学第一、第二定律。例如，对于定熵效率的计算公式：

$$\eta_{is} = \frac{h_{2s} - h_1}{h_2 - h_1}$$



## ❄️ 计算实例：R134a 循环性能
通过调用 **CoolProp** 库，我们实现了对制冷循环的自动化模拟：

| 参数名称 | 符号 | 数值 | 单位 |
| :--- | :---: | :---: | :---: |
| 蒸发温度 | $T_{evap}$ | -10 | °C |
| 冷凝温度 | $T_{cond}$ | 45 | °C |
| 性能系数 | $COP$ | 3.25 | - |

## 📈 结果可视化
开启 GitHub Pages 后，你可以直接展示生成的物性图表（如下图所示）：



---

## 🔗 在线预览
💡 **[点击进入本项目网页版说明书](https://你的用户名.github.io/你的仓库名/)**
