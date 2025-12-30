---
title: "我的第一篇物理笔记"
date: 2024-01-01
draft: false  # ⚠️ 记得改成 false，否则发布后别人看不到！
tags: ["Physics", "Simulation"]
categories: ["Research"]
---

## 1. 数学公式测试
麦克斯韦方程组的积分形式：
$$
\oint_{\partial \Omega} \mathbf{E} \cdot \mathrm{d}\mathbf{l} = - \frac{\mathrm{d}}{\mathrm{d}t} \int_{\Omega} \mathbf{B} \cdot \mathrm{d}\mathbf{S}
$$

## 2. 代码高亮测试
```python
import numpy as np
def schrodinger(psi, V):
    # Time-independent Schrödinger equation
    return -0.5 * np.diff(psi, 2) + V * psi