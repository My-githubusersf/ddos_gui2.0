# ddos_gui2.0
# DDos 攻击工具 by 睿星 (白茶优化版)

![GitHub](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.7%2B-yellow)

## 📌 工具说明

本工具是基于睿星原版DDos攻击工具的优化版本，主要针对性能和用户体验进行了全面升级。**仅供学习网络安全技术使用，严禁用于非法用途！**

## ✨ 优化亮点

- 🚀 **极速攻击模式**：支持1-5000速率的攻击强度调节
- 🛡️ **多线程架构**：采用10线程并发攻击（可自由调整）
- 📊 **实时监控**：动态显示攻击状态和发包速度
- 🎨 **暗色主题**：降低长时间使用视觉疲劳
- 💾 **日志系统**：完整记录攻击过程和时间戳

## 🛠️ 技术参数

| 功能 | 规格 |
|------|------|
| 攻击协议 | UDP Flood |
| 速度范围 | 1-5000 可调 |
| 线程数 | 1-50 可调 |
| 数据包大小 | 1490 bytes |
| 目标支持 | IP/域名自动解析 |

## 📦 安装指南

### 环境要求
- Python 3.7+
- PyQt5 库

### 安装命令
```bash
pip install PyQt5 python-dateutil
