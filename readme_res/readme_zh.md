# PotPlayer 的 ChatGPT 字幕翻译插件

该插件将 OpenAI 的 ChatGPT API 集成到 PotPlayer 中，以实现准确且上下文感知的字幕翻译。与传统翻译工具不同，ChatGPT 会考虑上下文、习语和文化细微差别，使其成为翻译字幕的理想解决方案。

---

## 安装

### 完全自动安装（推荐）
1. **下载安装程序**：  
   [完全自动安装程序](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/releases/download/exe_installer/installer.exe)  
   *(安装程序是开源的。)*  
2. **运行安装程序**：  
   - 双击 `installer.exe` 启动安装。  
   - 安装程序会自动检测 PotPlayer 的安装路径并完成设置。  

---

### 半自动安装
1. **下载 ZIP 文件**：  
   从本仓库获取最新的 ZIP 文件。  
2. **解压 ZIP 文件**：  
   将文件解压到临时文件夹。  
3. **运行 `setup.cmd` 脚本**：  
   - 双击 `setup.cmd` 安装插件。  
   - 仅当 PotPlayer 安装在默认路径 (`C:\Program Files\DAUM\PotPlayer`) 下时有效。  
   - 如果你使用了自定义安装路径，请参照下方的手动安装说明。

---

### 手动安装
1. **下载 ZIP 文件**：  
   从本仓库获取最新的 ZIP 文件。  
2. **解压 ZIP 文件**：  
   将文件解压到临时文件夹。  
3. **复制文件**：  
   将 `ChatGPTSubtitleTranslate.as` 和 `ChatGPTSubtitleTranslate.ico` 文件复制到以下目录：  
   ```
   C:\Program Files\DAUM\PotPlayer\Extension\Subtitle\Translate
   ```  
   如果你安装了 PotPlayer 的自定义路径，请相应修改该路径。

---

## 为什么选择 ChatGPT？

ChatGPT 通过考虑上下文、成语和文化细节来提供优质的字幕翻译。举个例子：

- 输入：*“You're gonna old yeller my f**king universe.”*  
  - **Google 翻译**：*“你要老了我他妈的宇宙吗?”* （不合逻辑）  
  ![](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/blob/master/readme_res/Google%20translate.png)
  - **ChatGPT**：*“你要像《老黄犬》一样对待我的宇宙?”* （准确地引用了电影 *老黄犬*，传达了原意）。  
  ![](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/blob/master/readme_res/Chatgpt.png)

这种上下文理解能力使 ChatGPT 在传统翻译工具中脱颖而出。

---

## 配置

1. 打开 PotPlayer `偏好设置`（`F5`）。
2. 进入 `扩展 > 字幕翻译`。
3. 选择 `ChatGPT Translate` 作为翻译插件。
4. 配置插件：
   - **模型名称**：输入你的 OpenAI 模型（例如 `gpt-4o` 或 `gpt-4o-mini`）。
   - **API 密钥**：提供你的 OpenAI API 密钥。
5. 根据需要设置源语言和目标语言。

---

## 功能

- **上下文感知翻译**：提供符合字幕意义和语气的翻译。  
- **文化细节**：保留成语和文化引用。  
- **开源**：所有代码和工具完全开源，透明可靠。  
- **高度可配置**：选择你喜欢的 OpenAI 模型并设置自定义翻译参数。  

---

## 注意事项

- **需要 API 密钥**：请从 [OpenAI](https://platform.openai.com/account/api-keys) 获取你的 API 密钥。  
- **自定义路径**：对于自定义 PotPlayer 安装路径，请遵循手动安装说明。

---

## 许可证

本项目采用 MIT 许可证。
