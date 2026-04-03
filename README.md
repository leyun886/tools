# Tools - 在线工具集

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/leyun886/tools/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/leyun886/tools)](https://github.com/leyun886/tools)
[![GitHub Issues](https://img.shields.io/github/issues/leyun886/tools)](https://github.com/leyun886/tools/issues)

**语言 / Language:** [简体中文](README.md) | [English](README.en.md)

---

一个轻量级、纯前端运行的在线工具集，保护您的隐私，所有操作均在本地完成。

🌐 **在线访问**: [https://tool.autogo.top/](https://tool.autogo.top/)

## 🛠️ 工具列表

### 📄 Log 文件浏览器
快速、强大的日志文件查看工具，支持：
- **40+ 种编码格式**：UTF-8、GBK、Big5、Shift_JIS 等
- **语法高亮**：自定义高亮规则，支持预设模板
- **正则过滤**：快速筛选包含特定模式的日志行
- **行折叠与修复**：处理多行日志，自动合并
- **自动滚动**：开启后会自动滚动到底部
- **导出功能**：导出过滤后的日志
- **JSON 格式化**：自动检测日志中的 JSON 内容，点击按钮即可格式化显示

### 🔤 正则表达式生成器
通过示例字符串自动生成正则表达式：
- **智能识别**：自动识别日期、时间、IP、邮箱等模式
- **多语言支持**：中文、英文、俄文、日文、韩文、法文、德文、西班牙文
- **实时测试**：即时验证生成的正则表达式
- **模式说明**：清晰的正则表达式解释
- **支持可变标记**：使用 `{{...}}` 标记可变内容

## 🚀 特点

- 🔒 **隐私保护**：所有操作在本地完成，数据不上传服务器
- 🌍 **多语言支持**：8 种语言界面
- 🎨 **深色主题**：护眼设计，适合长时间使用
- 📱 **响应式设计**：适配各种设备
- ⚡ **快速高效**：纯前端实现，无需后端

## 📖 使用说明

### Log 文件浏览器

1. 打开 [Log 文件浏览器](https://tool.autogo.top/log_viewer/)
2. 点击"打开文件"或拖拽文件到指定区域
3. 选择正确的编码格式（如不确定可尝试 UTF-8 或 GBK）
4. 使用搜索框快速定位内容
5. 使用正则过滤筛选日志
6. 可自定义语法高亮规则
7. **自动滚动**：勾选"自动滚动"复选框，每次内容变化时会自动滚动到底部
8. **JSON 格式化**：当日志行包含 JSON 内容时，行首会显示 `JSON` 按钮，点击即可格式化显示，再次点击恢复原样

### 正则表达式生成器

1. 打开 [正则表达式生成器](https://tool.autogo.top/regex_generator/)
2. 在输入框中输入示例字符串
3. 使用 `{{...}}` 标记可变内容，例如：`AI_Trader_EA XAUUSDm,{{M5}}: qwen3.5-plus-1`
4. 点击"生成正则"按钮
5. 在测试框中验证生成的正则表达式
6. 复制结果使用

## 💻 本地运行

```bash
# 克隆仓库
git clone https://github.com/leyun886/tools.git

# 进入目录
cd tools

# 使用任意 HTTP 服务器启动
# 方式 1: Python
python -m http.server 8080

# 方式 2: Node.js (需要安装 http-server)
npx http-server -p 8080

# 方式 3: PHP
php -S localhost:8080
```

然后在浏览器中访问 `http://localhost:8080/`

## 📁 目录结构

```
tools/
├── index.html              # 导航主页
├── log_viewer/
│   └── index.html          # Log 文件浏览器
├── regex_generator/
│   └── index.html          # 正则表达式生成器
├── 开发参考文档.json        # 开发文档和配置
└── README.md               # 项目说明
```

## 🌐 多语言支持

| 语言 | 代码 | 名称 |
|------|------|------|
| 简体中文 | zh-CN | 简体中文 |
| English | en | English |
| Русский | ru | Русский |
| 日本語 | ja | 日本語 |
| 한국어 | ko | 한국어 |
| Français | fr | Français |
| Deutsch | de | Deutsch |
| Español | es | Español |

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

## 📬 联系方式

- 📧 Email: [main@autogo.top](mailto:main@autogo.top)
- 💻 GitHub: [@leyun886](https://github.com/leyun886)

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 🙏 致谢

感谢所有使用和支持本项目的用户！

---

© 2026 Tools Navigator. Licensed under MIT.
