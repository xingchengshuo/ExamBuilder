# ExamBuilder / 智能组卷系统

**ExamBuilder** is a powerful, secure, and easy-to-use desktop application for managing question banks and generating exam papers.
**ExamBuilder** 是一款功能强大、安全且易用的桌面端应用，用于管理题库和生成试卷。

---

## 🌟 Key Features / 核心功能

*   **📝 Smart Import / 智能导入**:
    *   Manual entry with image support. / 支持手动录入及插入图片。
    *   **AI-Powered Import**: Paste text and let AI automatically structure it into questions. / **AI 智能导入**：粘贴文本，AI 自动将其结构化为题目。
*   **📄 One-Click Generation / 一键组卷**:
    *   Export professional `.docx` exam papers. / 导出专业的 `.docx` 试卷。
    *   Auto-formatting with LaTeX math support. / 自动排版，支持 LaTeX 数学公式。
*   **🔒 Security First / 安全优先**:
    *   Encrypted local data storage. / 本地数据加密存储。
    *   Optional password protection for the app. / 可选的程序启动密码保护。
*   **🤝 Sharing / 分享协作**:
    *   Export/Import encrypted `.xtk` question bank files. / 导出/导入加密的 `.xtk` 题库文件。

## 🚀 Installation / 安装说明

### Method 1: Installer (Recommended) / 方法 1：安装包（推荐）
Download the latest `.exe` installer from the [Releases](#) page and run it.
从 [Releases](#) 页面下载最新的 `.exe` 安装包并运行。

### Method 2: Run from Source / 方法 2：源码运行

1.  **Clone the repository / 克隆仓库**
    ```bash
    git clone https://github.com/yourusername/ExamBuilder.git
    cd ExamBuilder
    ```

2.  **Install Dependencies / 安装依赖**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the App / 运行应用**
    ```bash
    python main.py
    ```

## 📖 Usage Guide / 使用指南

1.  **Import Questions / 导入题目**:
    *   Go to the "Import" tab. / 进入“题库管理”标签页。
    *   Fill in details manually OR click "AI Import" to parse text. / 手动填写详情，或点击“AI 智能识别导入”解析文本。
    *   (Optional) Configure your AI API Key in Settings. / (可选) 在设置中配置 AI API 密钥。

2.  **Generate Exam / 生成试卷**:
    *   Go to the "Generate" tab. / 进入“组卷生成”标签页。
    *   Select subjects and question types. / 选择科目和题型。
    *   Click "Generate" to save as Word file. / 点击“生成试卷”保存为 Word 文件。

3.  **Share Questions / 分享题目**:
    *   Select questions in the list -> "Export Share File (.xtk)". / 在列表中选中题目 -> “导出分享题库 (.xtk)”。
    *   Share the file with others. They can double-click it to import. / 将文件分享给他人，双击即可导入。

## 🛠️ Configuration / 配置

*   **Data Location**: User data is stored in `%APPDATA%\ExamBuilder\data`.
*   **Settings**: You can customize fonts, header fields, and reset passwords in the "Settings" tab.
*   **数据位置**：用户数据存储在 `%APPDATA%\ExamBuilder\data`。
*   **设置**：可以在“系统设置”标签页自定义字体、试卷头字段及重置密码。

## 📄 Project Introduction / 项目详细介绍

For more details about the architecture, tech stack, and background, please read [PROJECT_INTRODUCTION.md](./PROJECT_INTRODUCTION.md).
关于架构、技术栈和背景的更多详情，请阅读 [PROJECT_INTRODUCTION.md](./PROJECT_INTRODUCTION.md)。

## 👤 Author / 作者

**邢城硕 (Xing Chengshuo)**

## 📜 License / 协议

This project is licensed under the MIT License.
本项目遵循 MIT 开源协议。
