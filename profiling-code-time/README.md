# Profiling

Use profiling to understand how much time each function call or line of code is taking in order to minimize delays or optimize code for time constrained software environment.

Using [this](https://www.youtube.com/watch?v=m_a0fN48Alw) tutorial from _youtube_

---

## Installations

```bash
pip install snakeviz
```

---

## Imports

```python
import cProfile
import pstats
```

---

## Implementation

There are two independent steps:

1. Basic Profilink Built-in Tool in **cPython**

2. Using **snakeviz** web server to visualize profiling done by **cPython**.

---
