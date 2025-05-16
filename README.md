# NeuroPrime

<div align="center">
  
![NeuroPrime Logo](https://img.shields.io/badge/Neuro-Prime-00ff00?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjMDBmZjAwIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCIgc3Ryb2tlLWxpbmVqb2luPSJyb3VuZCIgY2xhc3M9ImZlYXRoZXIgZmVhdGhlci1icmFpbiI+PHBhdGggZD0iTTkgMy42djQuMkg2LjVhMi41IDIuNSAwIDAgMCAwIDVoNS41Ij48L3BhdGg+PHBhdGggZD0iTTE1IDMuNnY0LjJoMi41YTIuNSAyLjUgMCAwIDEgMCA1SDE1Ij48L3BhdGg+PHBhdGggZD0iTTEyIDMuNnYxNi44Ij48L3BhdGg+PHBhdGggZD0iTTcgMTUuMmg0LjQiPjwvcGF0aD48cGF0aCBkPSJNMTcgMTUuMmgtMi44Ij48L3BhdGg+PHBhdGggZD0iTTggMTkuOGg4Ij48L3BhdGg+PC9zdmc+)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.10+-00ff00.svg)
![Framework](https://img.shields.io/badge/Framework-Gradio-00ff00.svg)

🧠 A 90s "hackerz" themed ChatGPT-like interface that unlocks advanced reasoning frameworks for deeper AI interactions

</div>

NeuroPrime combines nostalgia with cutting-edge AI capabilities, allowing you to dynamically select optimal reasoning strategies before sending queries to large language models. The app features a retro cyberpunk aesthetic with modern functionality, letting you combine two complementary reasoning frameworks to get more insightful responses from any OpenRouter-supported model.

## ✨ Features

- 🕹️ **Retro 90s "hackerz" UI** with scanlines, glitch effects, and terminal-inspired design
- 🧠 **Dynamic reasoning framework selector** that mixes two complementary approaches for enhanced results
- 🔐 **Encrypted API key storage** and model management system
- 📸 **Image upload support** for multimodal models
- 🌐 **Works with any OpenRouter-supported model**
- 🍎 **Native macOS application** with proper app bundle and system integration

## 🚀 Installation

### Prerequisites

- macOS 11.0 (Big Sur) or later
- Internet connection for accessing OpenRouter API
- Python 3.10+ installed (use the official Python.org installer for best compatibility)

### Quick Start - macOS

1. Download the latest release from the repository:
   ```
   https://github.com/aporeticaxis/neuroprime_test_fork/releases
   ```

2. Mount the DMG installer by double-clicking it

3. Drag NeuroPrime into your Applications folder

4. Launch the app from Launchpad or Applications folder

### Building from Source (for developers)

1. Clone the repository:
   ```bash
   git clone https://github.com/aporeticaxis/neuroprime_test_fork.git
   cd neuroprime_test_fork
   ```

2. Set up the Python environment and install dependencies:
   ```bash
   ./scripts/build.sh
   ```

3. Build the macOS application bundle:
   ```bash
   ./scripts/build_macos_app.sh
   ```

4. Run the application:
   ```bash
   open ./dist/NeuroPrime.app
   ```

### Build Process Details

The build scripts perform the following actions:

- **build.sh**: Sets up a Python virtual environment and installs required dependencies
- **build_macos_app.sh**: Creates the macOS application bundle (.app) with proper structure

## 👾 Usage

### API Key Setup
1. Register for an [OpenRouter](https://openrouter.ai) account
2. Generate an API key from your dashboard
3. Enter the API key in the NeuroPrime settings panel and click "S4V3 K3Y"

### Basic Operation

1. Type your query in the input field
2. Click "GET R34S0NING" to see what reasoning frameworks the AI suggests for your query
3. Click "S3ND M3SS4G3" to send your message enhanced with the hybrid reasoning approach

### Adding Models

1. Type the model name (e.g., "anthropic/claude-3-opus") in the "Add New Model" field
2. Click "ADD" to save it to your model list
3. Select the model from the dropdown to use it

### Using Images

If you're using a multimodal model that supports images:
1. Click the "Upload Image" button
2. Select the image from your device
3. Your image will be sent along with your text query

## 🧠 How It Works

NeuroPrime represents a new paradigm in AI interfaces. Here's what makes it special:

### Hybrid Reasoning Framework

Traditional AI interfaces simply send your query to the model. NeuroPrime takes a different approach:

1. It first analyzes your question and determines the optimal combination of reasoning frameworks
2. It selects TWO complementary approaches from all possible reasoning frameworks:
   - Inductive reasoning
   - Deductive reasoning
   - Abductive reasoning
   - Systems thinking
   - First principles reasoning
   - Lateral thinking
   - Critical reasoning
   - Bayesian reasoning
   - And many more...
3. It creates a hybrid prompt that instructs the AI to use both frameworks in tandem
4. It sends your query enhanced with this specialized reasoning approach

The result is responses that are more nuanced, accurate, and insightful than standard interactions.

## 🛠️ Technical Details

NeuroPrime for macOS is built with:

- **Gradio 5.23.3** for the web interface
- **Cryptography 41.0.7** for API key encryption
- **OpenRouter API** for model access
- **Python 3.10+** for core functionality
- **PyObjC** for macOS native integration
- **PyInstaller** for app bundling

Configuration is stored in your user directory:
- `~/Library/Application Support/NeuroPrime/config.json` - Stores your models and encrypted API key
- `~/Library/Application Support/NeuroPrime/key.bin` - Encryption key for securing your API key

## 📜 License

MIT License

## 🤝 Contributions

Contributions are welcome! Please feel free to submit a Pull Request.

## 🔮 Future Features

- Dark/Light mode toggle
- Chat history persistence
- Custom reasoning framework definitions
- Multiple conversation threads
- Export/import of conversations
- Mobile-responsive design
- Menu bar quick access for macOS

## ⚠️ Disclaimer

This is a personal tool built for enthusiasts. It's not affiliated with OpenRouter, OpenAI, or any other AI provider.

## 💻 Development

To set up a development environment on macOS:

```bash
# Clone the repository
git clone https://github.com/aporeticaxis/neuroprime_test_fork.git
cd neuroprime_test_fork

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app in development mode
python app.py
```

For faster development iterations, you can use the development mode which bypasses the need to rebuild the app bundle for each change:

```bash
# Run the app directly from source
python app.py
```

After making changes, if you want to test the packaged app:

```bash
# Rebuild the app bundle
./scripts/build_macos_app.sh

# Test the app bundle
open ./dist/NeuroPrime.app
```

## 🔧 Troubleshooting

### Usage Issues

**Q: My API key isn't saving.**  
A: Make sure the application has write permissions to the `~/Library/Application Support/NeuroPrime` directory.

**Q: The app crashes when I try to use a specific model.**  
A: Verify that the model name is correct and that it's available on OpenRouter.

**Q: The reasoning framework feature doesn't seem to be working.**  
A: Make sure to click "GET R34S0NING" before sending your message and that your API key is valid.

**Q: Images aren't being sent with my messages.**  
A: Confirm you're using a multimodal model that supports image inputs (like GPT-4 Vision).

### macOS-Specific Issues

**Q: The application is blocked by Gatekeeper.**  
A: Right-click (or Control-click) on the app in Finder and select "Open" from the context menu. When prompted, click "Open" to bypass Gatekeeper.

**Q: The app crashes on startup.**  
A: Make sure you have Python 3.10 or later installed. You can download it from python.org if needed.

**Q: I'm getting errors during the build process about Python not being found.**  
A: The macOS app build script looks for Python 3.10 in the official Python.org installation path. If you're using a different Python distribution (e.g., Homebrew, pyenv), consider installing the official Python.org version.

**Q: The app bundle doesn't create properly.**  
A: Make sure you run the scripts in the correct order: first `build.sh`, then `build_macos_app.sh`. If you encounter issues with icon generation, try running `package.sh` manually before building the app.

**Q: The DMG installer creation fails.**  
A: The `create_dmg.sh` script requires a properly built app bundle in the `dist` folder. Run `build_macos_app.sh` first, and make sure the app bundle is created successfully before attempting to create the DMG.

**Q: The app interface doesn't look right or shows blank screens.**  
A: NeuroPrime uses a browser-based interface powered by Gradio. If you experience rendering issues, try clearing your browser cache or try a different browser.

## 📚 Acknowledgments

- OpenRouter for providing a unified API for multiple language models
- The Gradio team for their amazing web interface library

---

<div align="center">
  <sub>Built with 💚 by hackers, for hackers</sub>
</div>
