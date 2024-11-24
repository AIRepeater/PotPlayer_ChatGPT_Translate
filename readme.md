# ChatGPT Subtitle Translation Plugin for PotPlayer

This plugin integrates OpenAI's ChatGPT API into PotPlayer for accurate and context-aware subtitle translation. Unlike traditional translation tools, ChatGPT considers context, idioms, and cultural nuances, making it the ideal solution for translating subtitles.

---

## Installation

### Fully Automatic Installation (Recommended)
1. **Download the Installer**:  
   [Fully Automatic Installer](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/releases/download/exe_installer/installer.exe)  
   *(The installer is open source also.)*  
2. **Run the Installer**:  
   - Double-click `installer.exe` to start the installation.  
   - The installer automatically detects PotPlayer's installation path and completes the setup.  

---

### Semi-Automatic Installation
1. **Download the ZIP File**:  
   Get the latest ZIP file from this repository.  
2. **Extract the ZIP File**:  
   Extract the contents to a temporary folder.  
3. **Run the `setup.cmd` Script**:  
   - Double-click `setup.cmd` to install the plugin.  
   - This works only if PotPlayer is installed in its default path (`C:\Program Files\DAUM\PotPlayer`).  
   - For custom installation paths, follow the manual installation instructions below.

---

### Manual Installation
1. **Download the ZIP File**:  
   Get the latest ZIP file from this repository.  
2. **Extract the ZIP File**:  
   Extract the contents to a temporary folder.  
3. **Copy Files**:  
   Copy `ChatGPTSubtitleTranslate.as` and `ChatGPTSubtitleTranslate.ico` to the following directory:  
   ```
   C:\Program Files\DAUM\PotPlayer\Extension\Subtitle\Translate
   ```
   Replace `C:\Program Files\DAUM\PotPlayer` with your custom PotPlayer installation path, if necessary.

---

## Why ChatGPT?

ChatGPT ensures superior subtitle translation by considering context, idioms, and cultural nuances. For example:

- Input: *"You're gonna old yeller my f**king universe."*  
  - **Google Translate**: *"你要老了我他妈的宇宙吗?"* (nonsensical).
  ![](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/blob/master/readme_res/Google%20translate.png)
  - **ChatGPT**: *"你要像《老黄犬》一样对待我的宇宙?"* (accurately referencing the movie *Old Yeller*, capturing the intended meaning).  
  ![](https://github.com/Felix3322/PotPlayer_Chatgpt_Translate/blob/master/readme_res/Chatgpt.png)

This level of contextual understanding sets ChatGPT apart from traditional translation tools.

---

## Configuration

1. Open PotPlayer `Preferences` (`F5`).
2. Navigate to `Extensions > Subtitle translation`.
3. Select `ChatGPT Translate` as the translation plugin.
4. Configure the plugin:
   - **Model Name**: Enter your OpenAI model (e.g., `gpt-4o` or `gpt-4o-mini`).
   - **API Key**: Provide your OpenAI API key.
5. Set the source and target languages as needed.

---

## Features

- **Context-Aware Translations**: Delivers translations that match the subtitle's meaning and tone.  
- **Cultural Nuances**: Preserves idiomatic expressions and cultural references.  
- **Open Source**: All code and tools are fully open source for transparency.  
- **Highly Configurable**: Choose your preferred OpenAI model and set custom translation parameters.  

---

## Notes

- **API Key Required**: Obtain your API key from [OpenAI](https://platform.openai.com/account/api-keys).  
- **Custom Paths**: For custom PotPlayer installation paths, follow manual installation instructions.

---

## License

This project is licensed under the MIT Licence.
