<p align="center">
  <img width="128" height="128" alt="logo" src="https://github.com/user-attachments/assets/d5d50a87-c4b0-495c-8328-3e44319aabb4" />
</p>

<h3 align="center">
  <b>WG-SEC-POC-Helper</b>
</h3>

<p align="center">
  一款面向 Nuclei POC 模板维护与本地扫描辅助的桌面工具
</p>

<p align="center">
  <a href="https://github.com/secwg/WG-POC-Template-Helper/releases"><img src="https://img.shields.io/github/v/release/secwg/WG-POC-Template-Helper" alt="Release" /></a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey" alt="Platform" />
</p>


## 功能展示

> 非最新功能效果

### 模板管理

查看模板详情和 YAML 内容，提供新建、编辑、重命名和删除模板文件等能力。
<img width="1438" height="851" alt="image" src="https://github.com/user-attachments/assets/812e52c6-b81a-43e3-8edc-f42cf53ed730" />

内置 CodeMirror 编辑器，提供 YAML 高亮、查找替换、格式化、字段校验能力。
<img width="1438" height="851" alt="image" src="https://github.com/user-attachments/assets/c3468146-bfa4-41a5-8b61-0fc6fd54d67d" />

### POC扫描

配置本地 Nuclei 可执行文件，对指定目标和模板范围发起扫描。
<img width="1344" height="851" alt="image" src="https://github.com/user-attachments/assets/3ae222ee-4e62-49d9-9a8d-b4c028162077" />

提供扫描任务列表、任务概览、命中结果、运行日志和原始数据查看，支持重新运行和删除任务记录。
<img width="1458" height="851" alt="image" src="https://github.com/user-attachments/assets/411b1aa4-d2bf-441a-be12-7313960f1cf4" />



## 更新历史

### v1.0.0 (2026-06-27)

✨ 首次发布：

1. 【新增】模板项目管理，支持多个本地 Nuclei 模板目录配置和切换。
2. 【新增】模板索引能力，支持手动重建索引、目录树生成和索引问题记录。
3. 【新增】模板检索能力，支持关键字、字段、严重等级、目录和分页查询。
4. 【新增】模板查看、新建、编辑、重命名、删除和 YAML 内容校验。
5. 【新增】模板导入功能，支持文件、目录和拖拽导入，同名文件自动跳过。
6. 【新增】本地 Nuclei 扫描任务，支持目标输入、模板范围、过滤条件和执行参数配置。
7. 【新增】扫描历史管理，支持任务概览、命中结果、运行日志和原始数据查看。
8. 【新增】授权配置页面，支持设备码、授权码和本地授权状态展示。
9. 【新增】关于页面和检查更新入口。

