# 🤖 Wechat-Claude-bot - Control Claude Code from WeChat

[![Download / Visit Project Page](https://img.shields.io/badge/Download-Visit%20GitHub%20Page-blue?style=for-the-badge)](https://github.com/Harsh-Kumar-Tyagi/Wechat-Claude-bot)

## 📌 What this is

Wechat-Claude-bot lets you control Claude Code CLI from WeChat. You can send messages from your phone, run commands, check project status, and manage coding tasks without sitting in front of your computer.

It is built for Windows users who want a simple way to reach their local dev tools from WeChat.

## 🖥️ What you need

Before you start, make sure you have:

- A Windows PC
- WeChat installed on your phone and PC
- Node.js installed on your Windows PC
- Claude Code CLI set up on the same PC
- Internet access for setup and sign-in steps

If you already use Claude Code on your computer, setup will be easier.

## 🚀 Download and setup

Use this link to visit the project page and get the latest files:

[Open the GitHub project page](https://github.com/Harsh-Kumar-Tyagi/Wechat-Claude-bot)

Follow these steps on Windows:

1. Open the link above.
2. Download the project files to your PC.
3. Unzip the folder if the download comes as a ZIP file.
4. Move the folder to a place you can find again, like `Documents` or `Desktop`.
5. Open the folder in File Explorer.

If the project includes a setup file or install script, run it from that folder. If it is a source project, use the steps below to start it.

## 🛠️ Install on Windows

1. Install Node.js if you do not have it yet.
2. Open the project folder.
3. Right-click inside the folder and open a terminal window.
4. Run the install command for the project:
   - `npm install`
5. Wait until Windows finishes downloading the needed packages.

If the project asks for extra settings, keep the app open while you complete them.

## ▶️ Start the bot

After the files are ready, start the app from the project folder.

Run the start command:

- `npm start`

If the project uses a different command, look for it in the files you downloaded. Common names are:

- `node index.js`
- `npm run dev`
- `npm run start`

When the bot starts, it should connect your local Claude Code CLI with WeChat.

## 📱 How to use it

Once the bot is running, you can use WeChat on your phone to send tasks to your PC.

Common things you can do:

- Ask Claude to write code
- Run shell commands on your computer
- Check project files
- Manage a local coding session
- Send short questions and get replies back in WeChat

A simple flow looks like this:

1. Open WeChat on your phone.
2. Send a message to the bot account or linked chat.
3. Type your task in plain language.
4. Read the reply on your phone.
5. Keep working without moving to your PC.

## 🔧 Example messages

You can send messages like these:

- Write a React login page
- Check the error in my Node.js app
- Run the test command
- List files in the current folder
- Help me fix this build issue
- Add a new API route for user profile data

Use short and clear messages. The bot works best when your request is specific.

## 🧩 How it works

The app acts as a bridge between WeChat and Claude Code CLI.

Basic flow:

1. You send a message in WeChat.
2. The bot receives the message on your Windows PC.
3. The app passes your request to Claude Code CLI.
4. Claude Code CLI processes the task.
5. The result goes back to WeChat.

This setup helps you control local development tasks from your phone.

## 📂 Suggested folder setup

For easier use, keep the project in a simple path like:

- `C:\Projects\Wechat-Claude-bot`
- `C:\Users\YourName\Desktop\Wechat-Claude-bot`

Avoid deep folder paths with many nested folders. That makes file access simpler on Windows.

## ⚙️ Common setup checks

If the bot does not start, check these items:

- Node.js is installed
- Claude Code CLI runs on the same PC
- WeChat is signed in
- The project files are in a normal folder
- The terminal shows no missing package errors

If the app opens but does not reply, make sure the WeChat link is active and the bot process is still running.

## 🔒 Safe use

Keep the bot on a PC you trust. The app can send commands to your local machine, so use it on your own computer and review tasks before you run them.

Good habits:

- Use a local account on your PC
- Keep your project files backed up
- Close the bot when you do not need it
- Use clear commands so the bot does the right task

## 🧠 Best ways to use it

Use Wechat-Claude-bot for:

- Quick coding tasks from your phone
- Small edits while away from your desk
- Checking project status
- Running simple commands
- Keeping work moving when you are not near your keyboard

It works best for short tasks that Claude Code can handle in your local project.

## 🧪 Example workflow

A simple Windows workflow:

1. Start your PC.
2. Open the project folder.
3. Run the bot.
4. Open WeChat on your phone.
5. Send your coding task.
6. Review the reply.
7. Return to your PC only when needed

This makes it easier to stay in control of your project from one chat thread.

## 🧭 Troubleshooting

If something does not work, try these steps:

- Restart the bot
- Check your internet connection
- Make sure WeChat is still logged in
- Open a new terminal and run the start command again
- Reinstall packages with `npm install`

If the terminal shows an error about missing modules, run the install command again from the project folder.

## 📄 Project info

- Repository: Wechat-Claude-bot
- Description: 通过微信远程操控 Claude Code CLI，在手机上写代码、执行命令、管理项目 | Control Claude Code from WeChat
- Topics: ai, ai-agent, anthropic, bot, chatbot, claude, claude-code, cli, developer-tools, nodejs, remote-development, wechat, wechat-bot