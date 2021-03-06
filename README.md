# rime-xhup
Rime 小鹤双拼音形输入方案，需要使用最新版的 librime（1.2.9+）。

## 特性

- 三种输入方式：

  - xhup 小鹤音形

    四键直接上屏，类似小鹤双拼飞扬版

  - xhup\_express 小鹤音形·连打

    类似朙月拼音，使用 `'` 或 `;` 分词，空格上屏

  - xhup\_fluency 小鹤音形·语句流

    语句流输入方式，使用 `'`、`;` 或空格分词，空格或回车上屏

- 简入繁出

- 类似朙月拼音的特殊符号输入

- 使用 `oi` 进行反查，反查码为 pinyin\_simp

- 「小鹤音形·连打」和「小鹤音形·语句流」支持造词、调频

## 文件说明

`xhup.dict.yaml`：字典文件，从小鹤双拼官方码表生成

`xhup.schema.yaml`：「小鹤音形」输入方案，依赖 `xhup.dict.yaml`

`xhup_express.schema.yaml`：「小鹤音形·连打」输入方案，依赖 `xhup.dict.yaml`

`xhup_fluency.schema.yaml`：「小鹤音形·语句流」输入方案，依赖 `xhup.dict.yaml`
