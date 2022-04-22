---
slug: sandbox
id: icck99npjw3e
type: challenge
title: Virtual Windows Desktop
teaser: Access a Windows desktop right from your browser
notes:
- type: text
  contents: "# Hello, Welcome to Instruqt \U0001F44B\n\nIn this track, we've prepared
    a sandbox environment so you can play around and experiment with your own Windows
    virtual desktop environment.\n\n\n\U0001F39B️ Instruqt tracks are self-contained
    virtual sandbox environments where you have full control over the configuration
    and setup.\n\n\U0001F4BB Users can access your demo from any web browser.\n\n☁️
    Shared cloud accounts are a thing of the past. With Instruqt temporary accounts,
    you can leave the cleanup to us.\n"
- type: text
  contents: |
    This sandbox environment shows how to interact with a Windows Desktop
    environment.
- type: text
  contents: |
    Please wait while we start your Windows Desktop.

    ![Windows Desktop](https://cdn.instruqt.com/assets/free-trial/windows-10-desktop.jpg)
tabs:
- title: RDP
  type: service
  hostname: guac
  path: /#/client/c/windows?username=instruqt&password=Passw0rd!
  port: 8080
- title: PowerShell
  type: terminal
  hostname: windows
- title: editor
  type: code
  hostname: windows
  path: C:\Users\instruqt\Documents
difficulty: basic
timelimit: 300
---
Welcome to your Windows Desktop.

The sandbox environment on the left shows three tabs. The first has an RDP session, the second shows an interactive PowerShell console, and the third has a code editor.
