# Echo VS Code Extension - Releases

Welcome to the official release page for **Echo**, a lightweight and intelligent Visual Studio Code extension designed to seamlessly integrate local AI models via [Ollama](https://ollama.com/) directly into your development workflow.

## 🚀 Key Features

* **Local & Private:** Runs entirely on your machine using Ollama with zero data leaks.

* **Smart Model Selection:** Echo automatically picks the most appropriate local model for your specific task so you don't have to configure it manually.

* **AI-Powered Code Generation:** Fast, offline coding assistance right inside VS Code.

* **Lightweight & Fast:** Simple integration without heavy overhead.

## 📥 Installation

Since this extension is distributed manually via `.vsix` files, follow these quick steps to install or update it:

1. Head over to the [Releases](../../releases) section of this repository.

2. Download the latest `.vsix` file (e.g., `echo-0.0.2.vsix`) from the assets.

3. Open your terminal in VS Code and run the following command to install it:

```
code --install-extension echo-0.0.2.vsix

```

*(Note: If you are updating from an older version, make sure to uninstall the previous version first using `code --uninstall-extension alidendenne.echo`)*

## 🛠️ Requirements

* [Ollama](https://ollama.com/) installed and running locally on your machine.

* Visual Studio Code version `1.60.0` or higher.
