# Tools - Online Tool Set

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/leyun886/tools/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/leyun886/tools)](https://github.com/leyun886/tools)
[![GitHub Issues](https://img.shields.io/github/issues/leyun886/tools)](https://github.com/leyun886/tools/issues)

**Language / 语言:** [English](README.en.md) | [简体中文](README.md)

---

A lightweight, pure front-end online tool set that runs locally to protect your privacy. All operations are completed locally without uploading data to any server.

🌐 **Online Access**: [https://tool.autogo.top/](https://tool.autogo.top/)

## 🛠️ Tool List

### 📄 Log File Browser
Fast and powerful log file viewer with support for:
- **40+ encoding formats**: UTF-8, GBK, Big5, Shift_JIS, and more
- **Syntax highlighting**: Custom highlight rules with preset templates
- **Regex filtering**: Quickly filter log lines containing specific patterns
- **Line folding and repair**: Handle multi-line logs with automatic merging
- **Export function**: Export filtered log content
- **JSON formatting**: Automatically detect JSON content in logs, click button to format and display

### 🔤 Regex Expression Generator
Automatically generate regular expressions from example strings:
- **Smart recognition**: Automatically identify patterns like dates, times, IPs, emails, etc.
- **Multi-language support**: Chinese, English, Russian, Japanese, Korean, French, German, Spanish
- **Real-time testing**: Instantly validate generated regular expressions
- **Pattern explanation**: Clear explanations of regex patterns
- **Variable markers**: Use `{{...}}` to mark variable content

## 🚀 Features

- 🔒 **Privacy protection**: All operations performed locally, data never uploaded
- 🌍 **Multi-language support**: 8 language interfaces
- 🎨 **Dark theme**: Eye-friendly design for extended use
- 📱 **Responsive design**: Adapts to various devices
- ⚡ **Fast and efficient**: Pure front-end implementation, no backend required

## 📖 Usage Instructions

### Log File Browser

1. Open [Log File Browser](https://tool.autogo.top/log_viewer/)
2. Click "Open File" or drag and drop a file to the designated area
3. Select the correct encoding format (try UTF-8 or GBK if unsure)
4. Use the search box to quickly locate content
5. Use regex filtering to filter logs
6. Customize syntax highlight rules
7. **JSON formatting**: When a log line contains JSON content, a `JSON` button will appear at the beginning of the line. Click to format and display, click again to restore

### Regex Expression Generator

1. Open [Regex Expression Generator](https://tool.autogo.top/regex_generator/)
2. Enter example strings in the input box
3. Use `{{...}}` to mark variable content, e.g., `AI_Trader_EA XAUUSDm,{{M5}}: qwen3.5-plus-1`
4. Click the "Generate Regex" button
5. Test the generated regular expression in the test box
6. Copy the result for use

## 💻 Running Locally

```bash
# Clone the repository
git clone https://github.com/leyun886/tools.git

# Enter the directory
cd tools

# Start with any HTTP server
# Method 1: Python
python -m http.server 8080

# Method 2: Node.js (requires http-server)
npx http-server -p 8080

# Method 3: PHP
php -S localhost:8080
```

Then visit `http://localhost:8080/` in your browser

## 📁 Directory Structure

```
tools/
├── index.html              # Navigation homepage
├── log_viewer/
│   └── index.html          # Log file browser
├── regex_generator/
│   └── index.html          # Regex expression generator
├── 开发参考文档.json        # Development documentation and config
└── README.md               # Project documentation (Chinese)
└── README.en.md            # Project documentation (English)
```

## 🌐 Multi-language Support

| Language | Code | Name |
|------|------|------|
| 简体中文 | zh-CN | 简体中文 |
| English | en | English |
| Русский | ru | Русский |
| 日本語 | ja | 日本語 |
| 한국어 | ko | 한국어 |
| Français | fr | Français |
| Deutsch | de | Deutsch |
| Español | es | Español |

## 📄 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

- 📧 Email: [main@autogo.top](mailto:main@autogo.top)
- 💻 GitHub: [@leyun886](https://github.com/leyun886)

## 🤝 Contributing

Issues and Pull Requests are welcome!

## 🙏 Acknowledgments

Thanks to all users who use and support this project!

---

© 2026 Tools Navigator. Licensed under MIT.
