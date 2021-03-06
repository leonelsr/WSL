---
title: Updating the WSL 2 Linux kernel
description: Instructions on how to update your WSL 2 Linux kernel manually
keywords: wsl, windows, linux kernel, windows subsystem for linux, kernel
ms.date: 03/12/2020
ms.topic: article
ms.localizationpriority: high
---

# Updating the WSL 2 Linux kernel

To manually update the Linux kernel inside of WSL 2 please follow these steps.

> [!NOTE] 
> If the installer can't find WSL 1, right-click the Linux kernel update installer and press "Uninstall", then rerun the installer.

## Download the Linux kernel update package

Please [download the latest WSL2 Linux kernel](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi) update package for x64 machines.

> [!NOTE]
> If you're using an ARM64 machine, please download the [ARM64 package](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_arm64.msi) instead.

## Install the Linux kernel update package

To install the Linux kernel update package:

  1. Run the update package downloaded in the previous step.

  2. You will be prompted for elevated permissions, select ‘yes’ to approve this installation.

  3. Once the installation is complete, you are ready to begin using WSL2!

## Future plans for updating the WSL2 Linux kernel

For more information, read the article [changes to updating the WSL2 Linux kernel](https://devblogs.microsoft.com/commandline/wsl2-will-be-generally-available-in-windows-10-version-2004), available on the [Windows Command Line Blog](https://aka.ms/cliblog).
