# 🧰 Money123  
一个基于 **MDUI + JS** 的轻量级金融信息仪表盘小工具。  
无需构建步骤，下载即用，可部署在 GitHub Pages 或其他静态托管平台。

---

## ✨ 功能一览
| 模块 | 描述 |
|---|---|
| 💰 **实时金价** | 调用公开接口，展示国内主要黄金品种价格、涨跌幅、最高/最低 |
| 📈 **股票查询** | 支持 POST / GET 两种请求方式，输入代码即可返回当日行情 |
| 🧮 **理财计算器** | ① 根据七日年化计算收益 ② 反推七日年化 |
| 🎨 **MDUI 组件** | 使用 Material Design 风格标签页、按钮、输入框等 |

---

## 🔗 在线预览
[https://kerzjz.qzz.io/Money123](https://kerzjz.qzz.io/Money123)  


---

## 🚀 本地运行
1. 克隆仓库  
   ```bash
   git clone https://github.com/kerzjz/Money123.git
   cd Money123
   ```
2. 直接打开  
   双击 `index.html` 即可本地运行；  
   或起任意静态服务器（VS Code Live Server / Python / Nginx 均可）。

---

## 🛠 技术栈
- 界面：[MDUI v1.0.2](https://www.mdui.org)（Material Design）
- 图标：[Font Awesome 6.4.0](https://fontawesome.com)
- 数据：  
  - 黄金价格 – [api.pearktrue.cn](https://api.pearktrue.cn)  
  - 股票行情 – [api.pearktrue.cn](https://api.pearktrue.cn)
- 构建：0 构建，纯 HTML / CSS / JS

---

## 📁 目录结构
```
Money123
├─ index.html          # 单文件仪表盘（可直接拷贝使用）
├─ README.md           # 本文件
├─ calc.html           # 计算器
├─ sec.html            # 股票
├─ gold.html           # 黄金
└─ LICENSE             # 开源许可协议
```
> 目前所有代码写在 `index.html` 内，方便一键部署；并拆分为多文件。

---

## 🤝 贡献指南
1. Fork 本仓库  
2. 新建分支 `feat/xxx` 或 `fix/xxx`  
3. 提交 PR 并描述改动内容  
欢迎提交 **Issue** 与 **Pull Request**！

---

## 📄 开源协议
暂无

---

## 🙋‍♂️ 作者
GitHub：[@kerzjz](https://github.com/kerzjz)  
如有问题，欢迎开 Issue 或私信交流。
