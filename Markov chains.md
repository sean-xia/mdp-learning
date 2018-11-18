

# 马尔科夫链

<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>


本节介绍马氏链（MC）的概念和性质。本文仅考虑有限离散时间过程。

## MC基础

定义一个随时间变化的**过程**， 令$X_t$表示一个随机变量，$t$为正整数。将该过程限定在某系统内部，系统包含不同的**状态** $S$, 也即是

```math
X_t\in S
```

