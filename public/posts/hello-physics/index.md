# 我的第一篇物理笔记


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

---

> 作者: [Lruihao](https://github.com/Lruihao)  
> URL: http://localhost:1313/posts/hello-physics/  

