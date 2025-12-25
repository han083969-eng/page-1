# 🚀 能源动力工程计算项目 (Energy & Power Analysis)

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Field](https://img.shields.io/badge/Field-Energy_and_Power-orange)
![Python](https://img.shields.io/badge/Python-3.9+-blue?logo=python)

> **声明**：本项目用于热力学循环计算与物性分析，基于 GitHub Pages 自动生成在线报告。

---

## 🛠️ 项目核心功能
* **物性查询**：集成 CoolProp 库，实现工质（如 R134a, 水蒸气）的快速查表。
* **循环分析**：支持卡诺循环、朗肯循环等效率分析。
* **自动化绘图**：自动生成 $T-s$ (温熵图) 与 $P-h$ (压焓图)。

---

## 📐 物理模型与公式
本项目遵循热力学第一定律。对于定熵效率的计算公式如下：

$$
\eta_{is} = \frac{h_{2s} - h_1}{h_2 - h_1}
$$



其中，$\eta_{is}$ 为定熵效率，$h$ 为单位质量焓值。

---

## 📊 计算结果示例

| 参数名称 | 符号 | 数值 | 单位 |
| :--- | :---: | :---: | :---: |
| 蒸发压力 | $P_{evap}$ | 0.24 | MPa |
| 冷凝压力 | $P_{cond}$ | 1.16 | MPa |
| 性能系数 | $COP$ | 3.52 | - |

---

## 🔗 在线访问
💡 **我的在线报告厅**：[点击这里查看本项目网页版](https://你的用户名.github.io/你的仓库名/)

---

© 2024 能动专业学生作品
