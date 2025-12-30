# SamFileTranslator

SamFileTranslator is a cross-platform desktop application built with **Material Avalonia**, supporting Windows, macOS, and Linux. It integrates advanced AI translation to locally process Word, Excel, PowerPoint, PDF, and image files—delivering accurate translations while keeping your data completely private.

SamFileTranslator 是一款基于 **Material Avalonia** 框架开发的跨平台桌面应用，支持在 Windows、macOS 和 Linux 系统上运行。它集成了先进的 AI 翻译能力，可本地化处理 Word、Excel、PowerPoint、PDF 及图片文件，在保护数据隐私的同时提供准确的翻译结果。

---

## ✨ Key Features 

- **🔒 Fully Local Processing, Zero Data Upload**
  
   File parsing, rendering, and formatting are all performed locally on your device. Only **text paragraph segments** are sent to the chosen AI model for translation. **No data is ever saved or stored elsewhere**.

- **📁 Full Format Support**

    Translates Word (`.docx`), Excel (`.xlsx`), PowerPoint (`.pptx`), PDF (`.pdf`), and common image formats (`.png`, `.jpg`, etc.) while **preserving original layouts and styles as much as possible**.
  
- **🌐 Flexible Bilingual Output**

   Output can be set to target language only, or side-by-side bilingual display with the option to arrange **source language first** or **target language first**.

- **⚙️ Customizable Translation Strategy**
  
   Improve accuracy and consistency for specialized documents by configuring translation domains, reference terms, and prohibited terms in Settings.

  
## ✨ 核心特性

- **🔒 完全本地处理，数据零上传**
  
  文件解析、渲染、格式重建均在本地完成，仅将拆分后的**文本段落**发送至所选 AI 模型进行翻译。**所有数据全程不落盘、不上传**。

- **📁 全格式支持**

  支持翻译 Word（`.docx`）、Excel（`.xlsx`）、PowerPoint（`.pptx`）、PDF（`.pdf`）及常见图片格式（`.png`, `.jpg` 等），并**最大程度保留原始排版与样式**。  

- **🌐 灵活的双语输出**

  支持仅输出目标语言，或同时输出源语言与目标语言的双语对照。双语模式下可自由选择**源语言优先**或**目标语言优先**的排列顺序。

- **⚙️ 可定制的翻译策略**  

  通过设置翻译领域、参考术语与禁用词表，可显著提升专业文档的翻译准确性与一致性。
  

## 🖼️ Application Interface  应用界面

| AI Model Selection  AI 模型选型         |
|----------------------------------------|
| <img width="600" height="500" alt="AI Interface" src="https://github.com/user-attachments/assets/42bb5fe2-5055-4724-a651-900bb2e2231f" /> |

| Setting Page  设置界面              |               
|------------------------------------|
| <img width="600" height="500" alt="settings" src="https://github.com/user-attachments/assets/bc8c1a00-bc1f-4af0-adae-1cf429565900" /> |

---

## 📄 Translation Output Examples  翻译输出效果示例

| Original Word Document  原文（Word 文档） | Target Language Only  仅输出目标语言 |
|-----------------------------------------|----------------|
| <img width="400" height="250" alt="DualLangOrg" src="https://github.com/user-attachments/assets/4c2a8921-04d6-41d8-a7d2-a138ef16c74d" /> | <img width="400" height="250" alt="DualNoRes" src="https://github.com/user-attachments/assets/9471abaa-2602-4d0e-9e59-3dd5af46b745" /> |

| Bilingual: Source First  双语输出：源语言在前 | Bilingual: Target First  双语输出：目标语言在前 |
|--------------------------------------------|------------------------|
| <img width="400" height="400" alt="dualLangRes" src="https://github.com/user-attachments/assets/44677a25-8a2e-4f1b-810a-b90ff77155c0" />  | <img width="400" height="350" alt="dualLangTargetFirst" src="https://github.com/user-attachments/assets/d2281774-a803-477a-b10d-ef76862f4c2f" /> |

---

## 📦 Download & Install

Visit the [Releases page](https://github.com/sams500/SamFileTranslator-Releases/releases/) to download the appropriate installer for your operating system and CPU architecture:

## 📦 下载与安装

请根据您的操作系统和 CPU 架构，在 [Releases 页面](https://github.com/sams500/SamFileTranslator-Releases/releases/) 下载对应的安装包：

- **Windows**: `.exe` (x64 / x86 / Arm64)  
- **macOS**: `.dmg` (Apple Silicon Arm64 / Intel x64)  
- **Linux**: `.deb`  (x64 / Arm64)
---

## 🚀 Quick Start

1. **Download and install** the version for your platform.  
2. Upon first launch, navigate to the **AI Model** page to configure your translation API key (by default, a public API key for Qwen is provided).
3. Drag and drop or select the file you wish to translate.  
4. Optionally, go to **Settings** to specify a translation domain and terminology for better accuracy.  
5. Choose your output language and dual language preference and other options.
6. Start translating.

## 🚀 快速开始

1. **下载并安装**对应平台的版本。
2. 首次启动后，在 **AI 模型** 页面配置可用的翻译模型和 API 密钥 (默认提供了Qwen公益API）。
3. 拖入或选择需要翻译的文件。
4. 根据需要，在 **设置** 中配置翻译领域与术语，以提升专业性。
5. 选择输出语言与双语模式等选项。
6. 开始翻译。

---

## ⚙️ Configuration Guide

- **AI Model Setup**: Supports multiple mainstream large language models. Apply for your own API key .  
- **Terminology Management**: Import custom glossaries to ensure consistent translation of specialized terms.  
- **Output Options**: Set default languages, dual language order, font scaling, and more.
  
## ⚙️ 配置说明

- **AI 模型设置**：支持多种主流大语言模型，需自行申请并填写对应 API Key。
- **术语管理**：可导入专业术语表，确保特定词汇翻译一致。
- **输出选项**：可设置默认语言对、双语排序、字体缩放等。

---

## 🔧 Tech Stack

- Framework: [Avalonia UI](https://avaloniaui.net/) (Material Theme)  
- Document Processing: Open XML + Official format SDKs 
- Translation Engine: Configurable AI model APIs (e.g., GPT, Qwen, etc.)  
- Platform: .NET 10 – truly cross-platform
  
## 🔧 技术栈

- 框架：[Avalonia UI](https://avaloniaui.net/) (Material Theme)
- 文档处理：Open XML + 各格式官方 SDK 
- 翻译引擎：可配置的 AI 模型 API（如 GPT、Qwen 等）
- 平台：.NET 10，真正跨平台

---

## 📄 License

Due to personal reason, the source code is not provided. But this project is free for personal and commercial use. Users are responsible for any costs incurred from AI translation services.

Welcome to support the public API key.

## 📄 许可证

由于个人原因源代码未开放，但本软件免费用于个人与商业用途，使用 AI 翻译服务产生的费用需用户自行承担。

非常欢迎支持公益API。
