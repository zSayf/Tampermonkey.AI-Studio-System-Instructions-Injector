# AI Studio System Instructions Injector

[![Greasy Fork Version](https://img.shields.io/greasyfork/v/551234?label=Greasy%20Fork&logo=tampermonkey&color=6a1b9a)](https://greasyfork.org/en/scripts/551234-ai-studio-system-instructions-injector)
[![Total Installs](https://img.shields.io/greasyfork/dt/551234?label=Installs&logo=tampermonkey)](https://greasyfork.org/en/scripts/551234-ai-studio-system-instructions-injector)
[![GitHub License](https://img.shields.io/github/license/zSayf/Tampermonkey.AI-Studio-System-Instructions-Injector)](https://github.com/zSayf/Tampermonkey.AI-Studio-System-Instructions-Injector/blob/main/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/zSayf/Tampermonkey.AI-Studio-System-Instructions-Injector)](https://github.com/zSayf/Tampermonkey.AI-Studio-System-Instructions-Injector/commits/main)

The definitive power-user script to supercharge your workflow in Google AI Studio. It provides a seamless and intelligent way to manage and inject your custom system instructions, designed to be fast, unobtrusive, and fully integrated with your workflow.

<p align="center">
  <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExeDVwdmYwbXZjZG9sZWN5ZWs1dm1zcnNkM3JsMmVyZ2NsZDJkMDkyNSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/F7a9IbhJbmM2vf3UlR/giphy.gif" alt="Script Demo GIF" width="80%">
</p>
---

## ✨ Key Features

*   **⚡ Instant, Flicker-Free Check**: On page load and when switching between chats, the script instantly checks if your instructions are already present by reading the UI directly. The button **only appears if needed**, giving you a clean workspace.
*   **🧠 SPA-Aware**: Fully compatible with AI Studio's single-page application design. The script automatically re-evaluates each chat you navigate to, ensuring context-aware functionality.
*   **🚀 One-Shot Workflow**: A single click on the sleek UI button is all it takes. It opens the panel, injects your text, closes the panel, and hides itself for maximum efficiency.
*   **🛡️ Safety First**: Intelligently detects if the instruction field already has text. Instead of blindly overwriting, it presents a clear confirmation dialog (`Overwrite` / `Cancel`) to protect your work.
*   **🎨 Professional UI**: Replaces all native browser dialogs with a custom-themed, professional UI that matches the AI Studio aesthetic, including non-blocking toast notifications.
*   **🔧 Total Control & Customization**:
    *   **First Run Setup**: On first use, you'll be prompted to set your own instructions.
    *   **Easy Editing**: Edit saved instructions anytime via a right-click on the button or through the Tampermonkey menu.
    *   **Closable Button**: Don't want to see the button? A small `X` allows you to hide it for the current session or permanently.
*   **🔗 Full Menu Integration**: Control everything directly from the Tampermonkey script menu:
    *   `Edit System Instructions`: Open the editor.
    *   `Inject Instructions (from Menu)`: Run the injection sequence, perfect for when the button is hidden.
    *   `► (Re)Show Button`: Easily bring the button back if you've hidden it permanently.

---

## 🛠️ Installation

1.  First, you need a user script manager. The most popular one is **[Tampermonkey](https://www.tampermonkey.net/)**.
2.  Click the link below to install the script from Greasy Fork:
    *   **[Install from Greasy Fork](https://greasyfork.org/en/scripts/551234-ai-studio-system-instructions-injector)**

---

## 📖 How to Use

1.  **First Run**: After installation, the script will prompt you to enter and save your custom system instructions. This only happens once.
2.  **Main Workflow**: A sleek button will appear at the bottom of the page if the current chat's instructions don't match yours.
    *   **Click** the button to perform the "one-shot" inject, close, and hide sequence.
    *   **Right-click** the button to open the editor and change your saved instructions.
3.  **Menu Controls**: For more options, click the Tampermonkey extension icon in your browser to access all the script's commands, including the option to re-show the main button.

---

## 📸 Screenshots

| Sleek & Unobtrusive UI | Professional Dialogs | Full Menu Control |
| :---: | :---: | :---: |
| ![The 'One-Shot' button appears at the bottom of the screen only when needed.](https://i.imgur.com/LOyQ9Az.png) | ![Custom-themed dialog for setting instructions.](https://i.imgur.com/3KCUJpG.png) | ![Control everything from the Tampermonkey menu.](https://i.imgur.com/RFhP38R.png) |

---

## 🤝 Contributing & Feedback

Found a bug or have a feature request? Please open an issue on the [GitHub repository issues page](https://github.com/zSayf/Tampermonkey.AI-Studio-System-Instructions-Injector/issues).

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
