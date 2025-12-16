# WHU-Supervisors-Info
武汉大学导师信息数据库

数据来源[武汉大学教师主页中文综合门户](https://jszy.whu.edu.cn/jssy.jsp?urltype=tree.TreeTempUrl&wbtreeid=1008)。每位教师文件以唯一的数字-字母组合 ID 命名，ID 即武大数据库分配 ID 。输入 https://jszy.whu.edu.cn/[ID]/zh_CN/index.htm 即可访问其个人主页。

筛去了没有具体信息的主页，余446份有效数据，涵盖武大各学院、机构。

包含每位老师的基本信息、团队信息、收受学生状态、教育背景、学术任职、专长领域、以及公开发表的论文数据等信息。Json schema 参考 [Json_schema.json](./Json_schema.json) 。使用 LLM 进行文本澄清与语义化分割。

数据爬取于 2025 年 12 月15 日。

欢迎提交 Pull requests 协助对本数据库的完善与改进。

使用请自便，在 Issue 区留下用途说明即可。
