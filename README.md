# sp

**项目状态 · 历史归档（2026-11-26）**。2019 年的 C 预测原语、Python ctypes 入口与 notebook。Makefile 只有构建共享库，当前树无验收说明。 补一页归档 README，列出两个原型库、样例 notebook 和未验证范围。

Archived C experiments in sequence prediction. The C sources are small shared-library prototypes with Python and notebook material alongside them.

- [sp.c](sp.c) implements the general prediction primitive.
- [s2p.c](s2p.c) contains specialized routines for two symbol widths.
- [Makefile](Makefile) contains the GCC build commands for `sp.so` and `s2p.so`.
- [c.py](c.py) and [sp.ipynb](sp.ipynb) record the exploratory Python usage.

The repository preserves the original experiments. A supported command-line program, package, and reproducible test run are undocumented.
