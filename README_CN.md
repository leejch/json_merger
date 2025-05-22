# JSON Merger

<br>简体中文 / [English](README.md)<br><br>

一个能合并结构不同JSON文件、补全缺失部分并保留主值的JSON合并器。

## 功能介绍

- 可合并结构不同的两个JSON文件；
- 保留主JSON的值优先，避免覆盖已有内容。

## 使用方式

1. 打开 [JSON Merger](https://leejch.github.io/json_merger/)；
2. 在`主JSON`输入框粘贴原始数据；
3. 在`补充JSON`输入框粘贴需要合并的数据；
4. 点击`合并`按钮；
5. 查看下方输出结果，可直接复制使用。

## 合并逻辑

- 两个JSON**结构可以不同**；
- `主JSON`与`补充JSON`中完全相同的内容不重复添加；
- 键相同但值不同时，保留`主JSON`的值；
- `主JSON`缺失的字段、对象、数组项将自动补充；
- 数组合并时避免重复。

## 版权与许可证

Copyright (C) 2025 [leejch](https://github.com/leejch)

本项目采用 [GPLv3 许可证](https://www.gnu.org/licenses/gpl-3.0.html) 开源发布。
你可以自由使用、修改和分发本软件，但必须保留原始版权信息，并在再发布时也使用 GPLv3 或兼容许可。

本程序按“原样”提供，不附带任何担保，包括适销性或适用于特定目的的适用性。
