# 📝 mdWorX - View and edit Markdown files easily

[![](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/threelobed-roughrider547/mdWorX/releases)

mdWorX brings powerful Markdown editing tools into Directory Opus. You can view, create, and change your notes without leaving your file manager. It provides a live preview as you type, so you see your formatting updates immediately.

## 📥 How to get mdWorX

Click the link below to go to the releases page. Choose the latest version file that ends in .opusplugin.

[Download mdWorX here](https://github.com/threelobed-roughrider547/mdWorX/releases)

## ⚙️ Installation steps

1. Open Directory Opus on your computer.
2. Click the gear icon or go to Settings and select Preferences.
3. Select the Plugins section in the left menu.
4. Click the Viewer Plugins or VFS Plugins button depending on your setup.
5. Click the Install button in the plugin window.
6. Find the file you downloaded earlier and select it.
7. Click Open to finalize the installation.
8. Restart Directory Opus to activate the new features.

## 🛠️ Features

mdWorX handles your technical documentation and personal notes with precision. It uses the CodeMirror 6 engine for fast text processing. The WebView2 component renders your Markdown pages with high visual fidelity.

*   **Live Preview**: The plugin shows a split-screen view. Your code sits on one side, and the formatted output sits on the other. 
*   **WYSIWYG Mode**: You see your bold, italic, and header styles immediately. 
*   **Marker Reveal**: Click any line in the preview to jump to that part of your raw text.
*   **Theme Support**: The editor uses your system colors to match your dark or light mode workspace.
*   **Full GFM Support**: The plugin understands GitHub Flavored Markdown, including tables, task lists, and code blocks.
*   **Encoding Check**: It reads files in any language without character errors.

## 💻 System requirements

*   Windows 10 or Windows 11.
*   Directory Opus 12 or newer.
*   Microsoft WebView2 Runtime (most Windows systems have this installed already).

## 🚀 Using the editor

Once you install the plugin, select any file with a .md extension inside Directory Opus. The viewer pane displays the contents automatically. To start editing, click the Edit button in the top toolbar of the viewer pane. 

The editor splits the window. You type your text on the left, and the right side updates the preview in real time. Use the icons at the top of the pane to toggle between text-only, split-view, and preview-only modes. 

## 🔧 Managing plugin settings

You can change how the editor looks through the Directory Opus settings menu. 

1. Go to Preferences.
2. Locate the Plugins category.
3. Select mdWorX from the list.
4. Click the Configure button to open a menu of options.

Here, you can choose if the editor shows line numbers or if it wraps long lines to fit the window. You can also pick a specific color scheme for the code editor if you prefer a different look than your system default.

## 🧠 Handling common issues

**The plugin does not load.**
Ensure you run a modern version of Directory Opus. Older versions lack the hooks required for this plugin to function. Check that you selected the correct file type during the installation process.

**The preview pane looks blank.**
This usually happens if the WebView2 Runtime is missing or outdated. Most recent Windows updates include this automatically. If you see a blank screen, visit the official Microsoft website to download the latest WebView2 Runtime installer.

**My formatting looks different.**
mdWorX follows the standard Markdown rules used by GitHub. If you use custom syntax, verify that it complies with the standard GFM format. The editor highlights potential syntax errors in red so you can fix them quickly.

## 🤝 Support and updates

The software stays current with regular updates. Check the download link occasionally to see if a newer version exists. If you encounter a bug, create an issue on this repository to let the developers know. Please describe the steps you took before the error occurred so others can help you solve the problem. 

This plugin aims to keep your workflow simple. It avoids complex buttons and confusing menus. Focus stays on your text and your files. By integrating with Directory Opus, mdWorX keeps your digital workspace tidy and organized. Treat this tool as a native part of your file management routine.