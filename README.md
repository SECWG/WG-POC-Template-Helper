<p align="center">
  <img width="128" height="128" alt="logo" src="https://github.com/user-attachments/assets/8abd21fa-2529-4939-8bcd-cb792bf95458" />
</p>

<h3 align="center">
  <b>WG-POC-Template-Helper</b>
</h3>

<p align="center">
  一款 Nuclei POC 模板维护工具，提供可视化的浏览、搜索、编辑和扫描功能
</p>


## 快速开始
1. **下载程序**：从 [Releases](https://github.com/secwg/WG-POC-Template-Helper/releases) 下载对应安装包。
2. **授权验证**：首次启动会弹出授权激活窗口，可复制设备码进入[授权中心](https://secwg.com/license-center)免费申请离线授权码，粘贴输入弹窗进行离校认证。
3. **配置项目**：进入"程序配置"模块，添加 POC 项目，配置项目名称 + POC 路径并保存。
4. **建立索引**：切换到"模板列表"模块，按照提示点击“建立数据索引“，等待索引完成自动扫描刷新数据。
5. **模板维护**：进入”模板管理“，维护管理 POC 文件。
6. **POC 扫描**：配置 Nulcei 路径，指定模板，参数进行扫描。



## 模块展示
### 模板列表
建立 POC 文件映射数据库，扫描提取 POC 核心字段，扫描 Nulcei template 1.2W 文件约 5S。提供常用多维度过滤，便于快捷浏览和检索，同时提供 POC 映射文件查看与编辑功能。
<img width="1184" height="729" alt="Snipaste_2026-02-19_22-21-44" src="https://github.com/user-attachments/assets/ab16d085-e2ea-40f9-bce9-64dc4b9d8c7d" />

<img width="1184" height="729" alt="Snipaste_2026-02-19_22-23-48" src="https://github.com/user-attachments/assets/92aacf1d-6b39-4af2-a841-9ab9ba924f6d" />

<img width="1184" height="729" alt="Snipaste_2026-02-19_22-27-48" src="https://github.com/user-attachments/assets/2108ba99-2c02-4b74-a7a8-8bd219326bda" />                                             

### 模板管理
直接对 POC 模板文件系统进行管理操作，提供对目录及 POC 模板文件的直接管理，的相关操作同步更新索引数据库。

<img width="1184" height="729" alt="Snipaste_2026-02-19_22-20-51" src="https://github.com/user-attachments/assets/dd4685c5-0ad3-462a-afd8-6626b61d1d43" />

<img width="1184" height="729" alt="Snipaste_2026-02-19_22-31-49" src="https://github.com/user-attachments/assets/30d89215-9e93-497e-915e-bb2ea1de4bf4" />

### POC 扫描
提供对 Nuclei 程序的调用，内置可视化常见参数配置，便于快捷扫描。
<img width="1184" height="729" alt="Snipaste_2026-02-19_22-33-38" src="https://github.com/user-attachments/assets/28a6647b-0183-4260-a36d-72ee58e0760d" />

### 程序配置
配置应用程序和授权信息。
<img width="1193" height="751" alt="Snipaste_2026-02-19_22-42-04" src="https://github.com/user-attachments/assets/b8d2861a-db39-4779-8003-e45faa451bbc" />

### 辅助工具[ToDo] 
提供额外的辅助功能

规划功能:

+ **请求测试** - 测试 HTTP/HTTPS 请求，验证 POC 的请求逻辑和响应处理。
+ **POC 转换** - 支持 Xray、Goby、Fscan 等常见 POC格式快捷转换。



## 授权说明
工具使用离线授权验证机制，无需联网，可访问 [授权中心](https://secwg.com/license-center) 提交设备码进行免费申请。
切换设备、授权码过期或切换最新版本，重新再次申请即可。


## 更新历史
### v1.0.0 (2026-02-20)
首次发布
1. 模板列表：浏览、搜索、过滤 POC
2. 模板管理：可视化编辑 POC 文件，
3. POC 扫描：集成 Nuclei 扫描引擎
4. 程序配置：多项目管理、授权管理配置
5. 离线授权：免费申请，离线验证
6. 数据索引：快速检索大型 POC 库

