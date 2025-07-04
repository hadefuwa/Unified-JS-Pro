# Unified JS Pro

**A Complete Professional Siemens WinCC Unified JavaScript Reference Tool**

[![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)
[![Version](https://img.shields.io/badge/version-1.3.0-brightgreen.svg)]()
[![Electron](https://img.shields.io/badge/Electron-Latest-47848F.svg)](https://electronjs.org/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![WinCC](https://img.shields.io/badge/WinCC-Unified-blue.svg)]()

## 🚀 Overview

Unified JS Pro is the **most comprehensive** desktop application for Siemens WinCC Unified JavaScript development. Built from official Siemens documentation, it provides a complete reference library of **54 professional templates** covering everything from basic JavaScript operations to advanced industrial HMI functions.

**Perfect for both beginners learning WinCC JavaScript and experienced developers needing quick access to industrial-grade code examples.**

![Unified JS Pro Screenshot](https://via.placeholder.com/800x500/1976d2/ffffff?text=Unified+JS+Pro+Screenshot)

## ✨ Features

### 🎯 **Complete Template Library**
- **54 Professional Templates** - Complete WinCC Unified JavaScript reference
- **16 Categories** - From basic operations to advanced industrial functions
- **Siemens Documentation Based** - All templates extracted from official documentation
- **Production Ready** - Real-world examples with error handling
- **Beginner Friendly** - Simple, readable code with detailed comments

### 💼 **Industrial-Grade Features**
- **File System Operations** - Production logging, configuration management
- **Timer Functions** - Delays, periodic operations, alarm blinking
- **Alarm Management** - Advanced filtering and subscription handling
- **Language Management** - Multi-language runtime switching
- **Screen Management** - Advanced popup control and object manipulation
- **Data Storage** - Session and screen-level DataSet management

### 🔧 **Professional Development Tools**
- **Smart Organization** - User templates prioritized, official templates categorized
- **Syntax Highlighting** - Beautiful JavaScript code highlighting with Prism.js
- **Template Management** - Create, edit, delete, and organize custom templates
- **Search & Filter** - Powerful search across templates, descriptions, and code
- **Import/Export** - Share template collections via JSON files
- **Copy & Paste Ready** - One-click code copying for TIA Portal

### 🎨 **User Experience**
- **Modern UI** - Professional Siemens-style interface
- **Dark Theme** - Easy-on-eyes code display
- **Responsive Design** - Optimized for various screen sizes
- **Real-time Feedback** - Template count and status updates
- **Keyboard Shortcuts** - Efficient navigation and operations

## 🛠️ Tech Stack

- **Electron.js** - Cross-platform desktop application framework
- **Node.js** - JavaScript runtime environment
- **HTML5/CSS3** - Modern web technologies
- **Vanilla JavaScript** - ES6+ features with beginner-friendly patterns
- **Prism.js** - Professional syntax highlighting
- **localStorage** - Client-side data persistence

## 📦 Installation

### Prerequisites
- Node.js >= 14.0.0
- npm >= 6.0.0

### Quick Start
```bash
# Clone the repository
git clone https://github.com/hadefuwa/Unified-JS-Pro.git

# Navigate to project directory
cd Unified-JS-Pro

# Install dependencies
npm install

# Start the application
npm start
```

## 🎯 Complete Template Categories

### **🔧 Core JavaScript Operations**
- **Array Operations** (6 templates) - Sorting, filtering, transformations
- **String Operations** (5 templates) - Concatenation, searching, formatting
- **Mathematical Operations** (3 templates) - Calculations, number formatting
- **Date & Time Operations** (4 templates) - Timestamps, formatting, calculations
- **Data Type Conversion** (3 templates) - Type conversions, validations
- **Loop Operations** (3 templates) - For loops, while loops, break/continue
- **Conditional Logic** (3 templates) - If-else chains, switch statements
- **Error Handling** (3 templates) - Try-catch blocks, error logging
- **Object Operations** (3 templates) - Object creation, property handling

### **🏭 Industrial WinCC Functions**
- **Screen Object Manipulation** (6 templates) - FindItem, color changes, visibility
- **File System Operations** (4 templates) - CreateDirectory, WriteFile, ReadFile, AppendFile
- **Timer Functions** (2 templates) - SetInterval, SetTimeout for delays and periodic tasks
- **Alarm Management** (1 template) - Advanced alarm subscription and filtering
- **Language Operations** (1 template) - Multi-language runtime switching
- **Screen Management** (2 templates) - Advanced popup control and screen analysis
- **Data Storage** (1 template) - Session and screen DataSet management

### **📚 Documentation Integration**
- **Official Siemens Documentation** - Converted PDF manuals included
- **Real-world Examples** - Production scenarios and industrial use cases
- **Best Practices** - Following Siemens coding standards and guidelines

## 🚀 Usage

1. **Browse Templates** - Explore 54 comprehensive templates across 16 categories
2. **Search & Filter** - Find specific WinCC functions quickly
3. **View Code** - See syntax-highlighted, production-ready JavaScript
4. **Copy Code** - One-click copying to clipboard for TIA Portal
5. **Create Custom** - Add your own project-specific templates
6. **Import/Export** - Share templates with development teams

## 📁 Project Structure

```
Unified-JS-Pro/
├── main.js                    # Electron main process
├── index.html                 # Application UI
├── renderer.js                # UI logic and interactions
├── templates.js               # Template management system
├── templates.json             # Complete template database (54 templates)
├── preload.js                 # Security preload script
├── package.json               # Dependencies and scripts
├── assets/                    # Application assets
│   └── favicon2.png          # Application icon
├── 109758536_Unified_JS_Styleguide_V10_en.txt    # Siemens documentation
├── 109758536_Unified_TipsScripting_V30_en.txt    # Siemens documentation
├── TECHNICAL_DOCUMENTATION.md # Developer documentation
├── FUTURE_ROADMAP.md         # Enhancement roadmap
└── README.md                 # This file
```

## 🔧 Development

### Development Mode
```bash
npm start
```

### Adding New Templates
Templates are managed through the comprehensive JSON database. You can:
- Add templates through the UI
- Import template collections from Siemens documentation
- Modify the complete template library

### Customization
- **Themes**: Modify CSS for different visual styles
- **Templates**: Extend the 54-template collection
- **Features**: Add new WinCC-specific functionality

## 📚 Documentation

- **[Technical Documentation](TECHNICAL_DOCUMENTATION.md)** - Complete developer guide
- **[Future Roadmap](FUTURE_ROADMAP.md)** - Planned enhancements and features
- **Included Siemens Documentation** - Official PDF manuals converted to text

## 🤝 Contributing

We welcome contributions! Please feel free to:
- Submit WinCC-specific templates
- Report bugs or suggest industrial features
- Add new Siemens function examples
- Improve documentation
- Submit pull requests

## 🎯 Industrial Use Cases

- **Professional HMI Development** - Complete WinCC Unified JavaScript reference
- **Industrial Automation** - Production-ready code templates
- **Team Collaboration** - Share templates across engineering teams
- **Training & Education** - Comprehensive learning resource for WinCC development
- **Code Standardization** - Consistent industrial coding patterns
- **Rapid Prototyping** - Quick access to complex WinCC functions
- **Production Systems** - Tested templates for real-world applications

## 🔒 Security

- Context isolation enabled
- Node integration disabled in renderer
- Secure preload script implementation
- Protected template database
- Input validation and sanitization

## 📈 Performance

- Efficient handling of 54+ templates
- Optimized rendering for large template collections
- Memory-conscious industrial application design
- Fast search across comprehensive template database
- Minimal startup time for production environments

## 🌟 What's New in Version 1.2.0

- **🎯 11 New WinCC Templates** - Critical industrial functions added
- **📈 Template Count**: 43 → 54 templates (+25% increase)
- **🏭 6 New Categories**: File System, Timers, Alarms, Language, Screen Management, Data Storage
- **📚 Siemens Documentation**: Official PDF manuals converted and integrated
- **💼 Industrial Focus**: Production-ready examples with real-world scenarios
- **🔧 Complete Reference**: Now covers all essential WinCC JavaScript functions

## 📄 License

This project is released into the public domain under the [Unlicense](LICENSE).

## 👨‍💻 Author

**Hamed Adefuwa**
- GitHub: [@hadefuwa](https://github.com/hadefuwa)

## 🙏 Acknowledgments

- Siemens for WinCC Unified platform and official documentation
- Industrial automation community
- Electron.js and Prism.js communities
- Open source contributors

---

**The Complete WinCC Unified JavaScript Reference - Made with ❤️ for Industrial Developers** 