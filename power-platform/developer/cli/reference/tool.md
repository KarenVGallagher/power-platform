---
title: Microsoft Power Platform CLI tool command group| Microsoft Docs
description: "Describes commands and parameters for the Microsoft Power Platform CLI tool command group."
keywords: "pac cli"
ms.subservice: developer
author: kkanakas
ms.author: kartikka
ms.date: 11/18/2022
ms.reviewer: jdaly
ms.topic: reference
contributors: 
 - JimDaly
---
<!-- 
Do not edit this file. 
This file is generated by a program and any changes will be overwritten when this topic is re-generated.
Use the include files to add additional content to this topic.
-->
# pac tool

Power Platform tools that can be installed and launched

[!INCLUDE [tool-intro](includes/tool-intro.md)]

## Commands

|Command|Description|
|---------|---------|
|[pac tool cmt](#pac-tool-cmt)|Launch Configuration Migration Tool (CMT)|
|[pac tool list](#pac-tool-list)|List the launchable tools and their local install state and version.|
|[pac tool pd](#pac-tool-pd)|Launch Package Deployer (PD)|
|[pac tool prt](#pac-tool-prt)|Launch Plug-in Registration Tool (PRT)|


## pac tool cmt

Launch Configuration Migration Tool (CMT)

[!INCLUDE [tool-cmt-intro](includes/tool-cmt-intro.md)]


### Optional Parameters

#### `--clear` `-c`

Clear tool from local file cache

This parameter requires no value. It is a switch.

#### `--update` `-u`

Update tool to latest available version from nuget.org

This parameter requires no value. It is a switch.

[!INCLUDE [tool-cmt-remarks](includes/tool-cmt-remarks.md)]

## pac tool list

List the launchable tools and their local install state and version.

[!INCLUDE [tool-list-remarks](includes/tool-list-remarks.md)]

## pac tool pd

Launch Package Deployer (PD)

[!INCLUDE [tool-pd-intro](includes/tool-pd-intro.md)]


### Optional Parameters

#### `--clear` `-c`

Clear tool from local file cache

This parameter requires no value. It is a switch.

#### `--update` `-u`

Update tool to latest available version from nuget.org

This parameter requires no value. It is a switch.

[!INCLUDE [tool-pd-remarks](includes/tool-pd-remarks.md)]

## pac tool prt

Launch Plug-in Registration Tool (PRT)

[!INCLUDE [tool-prt-intro](includes/tool-prt-intro.md)]


### Optional Parameters

#### `--clear` `-c`

Clear tool from local file cache

This parameter requires no value. It is a switch.

#### `--update` `-u`

Update tool to latest available version from nuget.org

This parameter requires no value. It is a switch.

[!INCLUDE [tool-prt-remarks](includes/tool-prt-remarks.md)]

[!INCLUDE [tool-remarks](includes/tool-remarks.md)]

### See also

[Microsoft Power Platform CLI Command Groups](index.md)<br />
[Microsoft Power Platform CLI overview](../introduction.md)