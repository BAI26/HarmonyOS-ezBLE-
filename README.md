# ezBLE 串口 (ezBLE Serial)

<div align="center">

![ezBLE Logo](https://via.placeholder.com/150x150.png?text=ezBLE+Logo) 
<!-- 替换为您实际的 Logo 图片链接 -->

**让物联网 IoT 硬件调试更现代、更直观**  
**Make IoT Hardware Debugging Modern & Intuitive**

[![HarmonyOS Next](https://img.shields.io/badge/HarmonyOS-Next-0052D9?logo=harmonyos&logoColor=white)](https://developer.huawei.com/consumer/cn/harmonyos)
[![AppGallery](https://img.shields.io/badge/AppGallery-Free_Download-C7000B?logo=huawei&logoColor=white)](#-下载与安装-download--install)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/badge/License-Apache%202.0-green)](./LICENSE)

[简体中文](#-简介-introduction) | [English](#-introduction)

</div>

---

## 📢 简介 (Introduction)

**ezBLE** 是一款专为 **HarmonyOS Next** 架构打造的原生多模物联网调试终端。它打破了传统串口工具的局限，集本地串口与 MQTT 云端调试于一身。

无论您是嵌入式工程师、创客还是学生，ezBLE 都能通过其实时波形示波器、3D 姿态同步以及强大的虚拟控台，为您提供“所见即所得”的现代化调试体验。

**ezBLE** is a native, multi-mode IoT debugging terminal built specifically for **HarmonyOS Next**. It breaks the limitations of traditional serial tools by seamlessly integrating local serial communication with MQTT cloud debugging.

Designed for embedded engineers, makers, and students, ezBLE offers a "What You See Is What You Get" modern debugging experience with real-time oscilloscopes, synchronous 3D attitude visualization, and a powerful virtual console.

---

## 🚀 下载与安装 (Download & Install)

🎉 **好消息！ezBLE 现已免费上架华为鸿蒙应用商店！**  
🎉 **Great News! ezBLE is now available for FREE on Huawei AppGallery!**

您可以直接在 HarmonyOS Next 设备上搜索 **"ezBLE"** 进行下载，体验最新功能。

> *[在此处放置商店二维码或链接]*
> *[Place AppGallery QR Code or Link Here]*

---

## ✨ 核心特性 (Key Features)

### 1. 📡 四模合一 (Quad-Mode Connectivity)
**CN:** 全面覆盖主流物联网场景，支持 Classic BT（经典蓝牙）、BLE（低功耗蓝牙）、USB 串口（OTG）以及 MQTT 协议。  
**EN:** Comprehensive coverage of mainstream IoT scenarios, supporting Classic BT, BLE, USB Serial (OTG), and MQTT protocols.

### 2. 📊 数据可视化 (Data Visualization)
**CN:** 拒绝枯燥的数据流。内置**实时波形示波器**，支持多通道数据绘图；特有 **IMU 传感器 3D 姿态同步解析**，实时复现硬件姿态。  
**EN:** Say goodbye to boring data streams. Features a built-in **Real-time Oscilloscope** for multi-channel plotting and a unique **IMU 3D Attitude Synchronization** to visualize hardware orientation in real-time.

### 3. 🎮 虚拟控台 (Virtual Console)
**CN:** 无需编写上位机代码。内置可配置**仪表盘**、**双摇杆遥控器**及 **HSV 调色板**，通过简单的协议即可控制您的硬件设备。  
**EN:** No need to write PC software. Includes a configurable **Dashboard**, **Dual-Stick Remote**, and **HSV Color Palette**, allowing you to control hardware with simple protocols.

### 4. 🛠 硬核辅助 (Pro Utilities)
**CN:** 专为开发者设计的辅助功能，包括 **Modbus CRC 自动校验**、定时循环发送任务以及完整的数据流日志保存与导出。  
**EN:** Built for developers, featuring **Modbus CRC Calculation**, timed transmission tasks, and comprehensive data stream logging and exporting.

---

## 💻 开发与贡献 (Development & Contribution)

**ezBLE 是一个完全开源的项目，我们热烈欢迎您参与到源代码的编写中！**  
**ezBLE is a fully open-source project, and we warmly welcome you to participate in the source code development!**

本项目基于 **ArkTS** 和 **ArkUI** 开发。无论您是鸿蒙开发的初学者还是资深专家，这里都是您施展才华的平台。

### 如何参与？(How to Contribute?)

1.  **Fork 本仓库**：将代码克隆到您的账户下。
2.  **开发新特性**：想要增加 Zigbee 支持？优化示波器算法？还是改进 UI 交互？请尽情发挥！
3.  **提交 PR (Pull Request)**：将您的代码提交给我们，我们将很高兴合并您的贡献。
4.  **共建鸿蒙生态**：让我们一起完善这个项目，为物联网开发者提供更好的工具。

*   **Tech Stack**: HarmonyOS Next, ArkTS, ArkUI
*   **We need help with**: New protocol support, UI/UX improvements, Localization, and Bug fixes.

---

## 📸 截图预览 (Screenshots)

| 连接管理 (Connection) | 示波器 (Oscilloscope) | 虚拟控台 (Console) |
| :---: | :---: | :---: |
| ![Connect](https://via.placeholder.com/200x400?text=Connect) | ![Scope](https://via.placeholder.com/200x400?text=Scope) | ![Console](https://via.placeholder.com/200x400?text=Console) |
<!-- 请替换为实际的应用截图链接 -->

---

## 🤝 反馈与交流 (Feedback)

如果您在使用过程中遇到任何问题，欢迎提交 [Issue](issues)。

If you encounter any issues, please feel free to submit an [Issue](issues).

## 📄 许可证 (License)

本项目遵循 [Apache-2.0 License](./LICENSE) 开源协议。
This project is licensed under the [Apache-2.0 License](./LICENSE).

---

<div align="center">
Made with ❤️ for HarmonyOS Next Developers
</div>
