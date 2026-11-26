# sp

**项目状态 · 历史归档。** 保留 C 序列预测原型、共享库构建脚本与 Python 使用笔记。

Archived C experiments in sequence prediction. The C sources are small shared-library prototypes with Python and notebook material alongside them.

- [sp.c](sp.c) implements the general prediction primitive.
- [s2p.c](s2p.c) contains specialized routines for two symbol widths.
- [Makefile](Makefile) contains the GCC build commands for `sp.so` and `s2p.so`.
- [c.py](c.py) and [sp.ipynb](sp.ipynb) record the exploratory Python usage.

The repository preserves the original experiments. A supported command-line program, package, and reproducible test run are undocumented.
