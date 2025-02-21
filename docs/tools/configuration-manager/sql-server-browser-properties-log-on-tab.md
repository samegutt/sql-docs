---
title: "SQL Server Browser Properties (Log On Tab)"
description: Learn about the Log On tab of the SQL Server Browser Properties dialog box. See how to use this tab to specify an account and to start or stop the service.
ms.custom: seo-lt-2019
ms.date: "03/14/2017"
ms.prod: sql
ms.prod_service: sql-tools
ms.reviewer: ""
ms.technology: tools-other
ms.topic: conceptual
ms.assetid: c77871ec-c2f4-4e4a-9a10-5aeb4ae70507
author: markingmyname
ms.author: maghan
monikerRange: ">=sql-server-2016"
---
# SQL Server Browser Properties (Log On Tab)
[!INCLUDE [SQL Server Windows Only](../../includes/applies-to-version/sql-windows-only.md)]
  The [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser program runs as a service on the server. [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser listens for incoming requests for [!INCLUDE[msCoName](../../includes/msconame-md.md)] [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] resources and provides information about [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] instances installed on the computer.  
  
 [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser listens on a UDP port and accepts unauthenticated requests using [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Resolution Protocol (SSRP).  
  
 Changing the password of an account takes effect immediately without restarting the service.  
  
## Options  
 **Local System account**  
 Run the [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser service in the security context of the Local System account. When possible, use a low-permission account instead.  
  
 **This account**  
 Specify a local or domain user account that uses Windows Authentication. We recommend using a domain user account with minimal rights for services. For information about selecting an account, see "Setting Up Windows Service Accounts" in [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Books Online.  
  
 **Browse**  
 Browse for a user or built-in security principal.  
  
> [!IMPORTANT]  
>  Use a low-permission account. For information about the permissions required for the [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser Service, see the Security section of [SQL Server Browser Service](../../tools/configuration-manager/sql-server-browser-service.md).  
  
 **Password**  
 Enter the password of the security principal.  
  
 **Confirm password**  
 Confirm the password of the security principal.  
  
 **Service status**  
 Indicates whether this service is running, stopped, or disabled. "**...**" indicates a state change is pending.  
  
 **Start**  
 Start the [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser service.  
  
 **Stop**  
 Stop the [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser service.  
  
 **Pause**  
 Pause the [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser service.  
  
 **Resume**  
 Resume a paused [!INCLUDE[ssNoVersion](../../includes/ssnoversion-md.md)] Browser service.  
  
## See Also  
 [SQL Server Browser Service](../../tools/configuration-manager/sql-server-browser-service.md)  
  
  
