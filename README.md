# 将MHF早期任务批量转换为MH2Dos任务的工具 #

### 大致描述 ###

通过一系列，数据处理，指针处理。将怪物猎人边境早期的服务器任务，转换为PS2 怪物猎人2Dos 本地自制任务或2Dos联机服务器可用任务

### 使用前提 ###

PS：本工具先需要将ReFrontier将MHF任务解密；
尽可能只用MHF早期任务，MHF后期任务内容早已和2Dos完全不一样，转换将没有意义。

在工具统计目录下：
创建Input文件夹，放置用于转换的MHF任务文件（已解密）
创建Out文件夹，用于输出文件

### 一些特殊处理 ###

若发现属于仅MHF有道具，2Dos的道具。如报酬道具，将替换为【不可燃烧的废物】。
若任务星星超过2Dos的最大8，则修正为8
若怪物ID、地图ID等超出最大范围，会提示。并不建议使用。