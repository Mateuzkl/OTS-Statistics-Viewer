# 📊 TFS Statistics Viewer

> **Complete and professional HTML viewer for TFS (The Forgotten Server) Statistics logs**

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-blue?style=for-the-badge)](https://mateuzkl.github.io/OTS-Statistics-Viewer/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

---

## ✨ About the Project

The **TFS Statistics Viewer** is a modern and intuitive web tool that transforms complex TFS (The Forgotten Server) Statistics logs into clear and actionable visualizations. Developed with focus on user experience, it offers deep performance analysis for TFS source code and Lua scripts without requiring installation or configuration.

## 🎯 Key Features

### 🗂️ Multi-Tab Interface
- **📈 Overview** - Dashboard with general statistics and performance summary
- **⚡ Dispatcher** - Detailed analysis of thread dispatcher tasks and C++ source performance
- **📜 Lua Scripts** - Lua script execution monitoring and performance tracking
- **🗄️ SQL Queries** - Database query tracking and optimization insights
- **🐌 Slow Logs** - Highlighted slow and very slow operations in TFS source
- **❓ How to Use** - Integrated complete tutorial

### 🚀 Advanced Features

#### 📁 Smart Upload
- Upload **multiple TFS log files** simultaneously
- Automatic parsing of TFS Statistics formats
- Support for different log types (dispatcher, lua, sql, source analysis, etc.)

#### 🎨 Rich Visualization
- **Visual performance indicators** for TFS source code analysis (colors, progress bars)
- **Metric cards** with key data (CPU usage, players online, slow operations)
- **Detailed tables** with all TFS log data
- **Progress bars** for resource usage percentage
- **Color-coded tags** for slow/very slow TFS operations

#### 🔍 Advanced Analysis
- **Smart filters** by C++ function/Lua script/SQL query
- **Flexible sorting** by execution time/calls/resource usage
- **Automatic detection** of TFS performance issues:
  - CPU > 50%
  - Operations > 100ms
  - Memory leaks in Lua scripts
  - Slow database queries
- **Code with syntax highlighting** for C++ and Lua

#### 📱 Responsive Design
- Adaptive interface for **mobile/desktop**
- Optimized experience on all devices
- **Works offline** - no server required for TFS analysis

## 🛠️ How to Use

### 🌐 Online Access (Ready to Use)
1. 🚀 Visit: **[https://mateuzkl.github.io/OTS-Statistics-Viewer/](https://mateuzkl.github.io/OTS-Statistics-Viewer/)**
2. 📤 Upload your `.log` files using the upload buttons
3. 📊 Analyze performance through the different tabs
4. ✨ No installation required - works directly in your browser!

## 📋 Usage Examples

The viewer automatically interprets TFS logs like:

```log
[2024-01-15 10:30:45] Dispatcher: std::move(f) - 4471ms (VERY SLOW)
[2024-01-15 10:30:46] Lua Script: onUse - 150ms (SLOW)
[2024-01-15 10:30:47] SQL Query: SELECT * FROM players - 25ms
[2024-01-15 10:30:48] C++ Function: Player::addItem - 89ms
[2024-01-15 10:30:49] Lua Event: onThink - 45ms
```

### 🔍 Automatic TFS Performance Detection
- ⚠️ **Critical C++ operations** like the `4471ms` operation in `std::move(f)`
- 🐌 **Slow Lua scripts** that impact server performance
- 📊 **Heavy SQL queries** with high execution time
- 💾 **Memory usage** in TFS source code
- 🔧 **Thread dispatcher** bottlenecks
- 📜 **Lua script optimization** opportunities

## 🎨 Screenshots

### TFS Performance Dashboard
![Dashboard](https://via.placeholder.com/800x400/2196F3/FFFFFF?text=TFS+Performance+Dashboard)

### C++ Dispatcher Analysis
![Dispatcher](https://via.placeholder.com/800x400/FF9800/FFFFFF?text=C%2B%2B+Dispatcher+Analysis)

### Lua Script Monitoring
![Lua Scripts](https://via.placeholder.com/800x400/4CAF50/FFFFFF?text=Lua+Script+Performance)

---

<div align="center">

### 🌟 If this project was helpful, consider giving it a star!

**[⭐ Star on GitHub](https://github.com/mateuzkl/OTS-Statistics-Viewer)** | **[🌐 Live Demo](https://mateuzkl.github.io/OTS-Statistics-Viewer/)**

</div>

---

<div align="center">
  <sub>Made with ❤️ for The Forgotten Server community</sub>
</div>