---
slug: sandbox
id: icck99npjw3e
type: challenge
title: Virtual Windows Desktop
teaser: Access a Windows desktop right from your browser
notes:
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
  hostname: powershell
- title: Example
  type: service
  hostname: windows
  port: 8080
- title: editor
  type: code
  hostname: guac
  path: C:\Users\instruqt\Documents
difficulty: basic
timelimit: 6000
---
Welcome to your Windows Desktop.

The sandbox environment on the left shows two tabs. The first has an RDP session, and the second shows an interactive PowerShell console.
