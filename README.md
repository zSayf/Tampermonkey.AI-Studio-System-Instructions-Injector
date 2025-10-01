# Tampermonkey AI Studio System Instructions Injector

Supercharge your Google AI Studio workflow with the ultimate power-user script. This Tampermonkey script provides a professional, fully-controllable interface to rapidly inject your custom system instructions, only appearing when it's actually needed.

![Showcase](https://i.imgur.com/your-gif-url.gif)  <!-- You can create a short GIF showcasing the script in action and replace this URL -->

---

## ✨ Core Features

This script was built from the ground up to be smart, efficient, and unobtrusive.

- **🚀 Instant, Flicker-Free Check**: On page load and between navigating chats, the script performs an instant check by reading the page's state. The UI button **only appears if your instructions aren't already there**, giving you a completely clean workspace.
- **⚡ 'One-Shot' Workflow**: A single click on the sleek bottom-tab button performs a full sequence: it opens the panel, injects your text, closes the panel, and then hides itself.
- **🔒 Safety First**: Intelligently detects if instructions already exist. Instead of blindly overwriting, it presents a clean confirmation dialog (`Overwrite` / `Cancel`) to protect your work.
- **🎨 Professional UI**: Replaces all ugly native browser `prompt()` and `alert()` boxes with a custom-themed, non-blocking UI, including modals and toast notifications that match the AI Studio aesthetic.
- **🧠 SPA-Aware**: Fully aware of AI Studio's single-page application structure. The script automatically re-runs its check whenever you switch between different chats, ensuring it's always relevant to the conversation you're in.
- **⚙️ Total Control & Customization**:
    - **First Run Setup**: On first use, it prompts you to set your own default instructions.
    - **Easy Editing**: Edit your saved instructions anytime via a right-click on the button or a dedicated command in the Tampermonkey menu.
    - **Closable Button**: Don't want to see the button? Click the '×' to hide it for the session or permanently.
    - **Full Menu Integration**: Control everything from the Tampermonkey menu, including editing, direct injection (perfect if the button is hidden), and an option to re-show the button if you've hidden it forever.

---

## 🛠️ Installation

1.  **Install a User Script Manager**: You need a browser extension to run this script. The most popular one is [**Tampermonkey**](https://www.tampermonkey.net/).
2.  **Install the Script**: Click on the installation link (e.g., from Greasy Fork) and your script manager will prompt you to install it.
3.  **Done!**: Simply navigate to [Google AI Studio](https://aistudio.google.com/), and the script will run automatically.

---

## 🕹️ How to Use

- **First Use**: Upon first launch, a professional-looking dialog will appear, asking you to enter and save your custom system instructions. This text will be saved locally in your browser.
- **Injecting Instructions**: If the script detects that the current chat does not have your instructions, a "INJECTOR" button will appear at the bottom of the page.
  - Click it once to perform the 'one-shot' inject, close, and hide sequence.
  - If the field already has text, a confirmation dialog will appear.
- **Editing Instructions**:
  - **Method 1**: Right-click the "INJECTOR" button.
  - **Method 2**: Click the Tampermonkey extension icon in your browser, and select "Edit System Instructions".
- **Hiding/Showing the Button**:
  - **To Hide**: Click the small '×' on the button to hide it temporarily (for the session) or permanently.
  - **To Re-Show**: If you've hidden it permanently, click the Tampermonkey icon and select "► (Re)Show Button", then refresh the page.

---

## 📜 License

This project is licensed under the MIT License.
