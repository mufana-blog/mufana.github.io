---
title: "Unblock files with PowerShell"
date: 2017-08-10
excerpt: "Unblock files with a PowerShell oneliner!"
comments: true
tags: 
- PowerShell 
- SQL
Catagories: PowerShell
author_profile: true
---

# Unblock files with PowerShell

A simple oneliner to unblock files with PowerShell.

```powershell
Get-ChildItem -recurse "PathToFilesOrFolder" | Unblock-File -verbose
````
