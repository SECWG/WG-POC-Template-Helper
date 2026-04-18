<p align="center">
  <img width="128" height="128" alt="logo" src="https://github.com/user-attachments/assets/8abd21fa-2529-4939-8bcd-cb792bf95458" />
</p>

<h3 align="center">
  <b>WG-POC-Template-Helper</b>
</h3>

<p align="center">
  一款 Nuclei POC 模板维护工具，提供可视化的浏览、搜索、编辑和扫描功能
</p>

<p align="center">
  <a href="https://github.com/secwg/WG-POC-Template-Helper/releases"><img src="https://img.shields.io/github/v/release/secwg/WG-POC-Template-Helper" alt="Release" /></a>
  <a href="https://secwg.com/license-center"><img src="https://img.shields.io/badge/license-Free-green" alt="License" /></a>
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS-lightgrey" alt="Platform" />
</p>

---

## 快速开始

1. **下载程序**：从 [Releases](https://github.com/secwg/WG-POC-Template-Helper/releases) 下载对应平台安装包。
2. **授权验证**：首次启动弹出授权激活窗口，复制设备码前往 [授权中心](https://secwg.com/license-center) 免费申请授权码，粘贴后点击激活。
3. **配置项目**：进入「程序配置」，添加 POC 项目（名称 + 路径），可选配置 Nuclei 可执行文件路径，保存。
4. **建立索引**：切换到「模板列表」，按提示点击「建立数据索引」，等待扫描完成（1.2 万文件约 5 秒）。
5. **模板维护**：进入「模板管理」，对 POC 文件和目录进行增删改操作。
6. **POC 扫描**：在「POC 扫描」中配置目标、模板和参数，一键调用 Nuclei 执行扫描。

---

## 模块展示

### 模板列表

建立 POC 文件映射数据库，提取核心字段，支持多维度过滤检索，可直接查看和编辑 POC 内容。

<img width="1184" height="729" alt="模板列表" src="https://github.com/user-attachments/assets/ab16d085-e2ea-40f9-bce9-64dc4b9d8c7d" />

<img width="1184" height="729" alt="模板列表-详情" src="https://github.com/user-attachments/assets/92aacf1d-6b39-4af2-a841-9ab9ba924f6d" />

<img width="1184" height="729" alt="模板列表-编辑" src="https://github.com/user-attachments/assets/2108ba99-2c02-4b74-a7a8-8bd219326bda" />

### 模板管理

直接操作 POC 文件系统，支持目录和文件的增删改，相关操作自动同步更新索引数据库。

<img width="1184" height="729" alt="模板管理" src="https://github.com/user-attachments/assets/dd4685c5-0ad3-462a-afd8-6626b61d1d43" />

<img width="1184" height="729" alt="模板管理-编辑" src="https://github.com/user-attachments/assets/30d89215-9e93-497e-915e-bb2ea1de4bf4" />

### POC 扫描

可视化配置 Nuclei 扫描参数，支持指定模板、模板目录、自定义路径三种模式，一键启动扫描。

<img width="1184" height="729" alt="POC扫描" src="https://github.com/user-attachments/assets/28a6647b-0183-4260-a36d-72ee58e0760d" />

### 程序配置

管理 POC 项目、Nuclei 路径配置及授权信息。

<img width="1193" height="751" alt="程序配置" src="https://github.com/user-attachments/assets/b8d2861a-db39-4779-8003-e45faa451bbc" />

### 辅助工具（规划中）

- **请求测试** - 测试 HTTP/HTTPS 请求，验证 POC 请求逻辑和响应处理
- **POC 转换** - 支持 Xray、Goby、Fscan 等常见格式快捷转换

---

## 授权说明

采用在线授权验证机制，首次激活需联网。访问 [授权中心](https://secwg.com/license-center) 提交设备码免费申请授权码。

- 授权码与设备绑定，切换设备需重新申请
- 每次授权有效期 120 天，到期后可随时免费续期
- 程序版本更新后需重新申请对应版本授权码

---

## 更新历史

### v1.0.0 (2026-02-20)

首次发布

- 模板列表：浏览、搜索、多维度过滤 POC
- 模板管理：可视化编辑 POC 文件和目录
- POC 扫描：集成 Nuclei 扫描引擎，可视化参数配置
- 程序配置：多项目管理、授权信息管理
- 离线授权：免费申请，离线验证
- 数据索引：快速检索大型 POC 库，支持 Windows / macOS
