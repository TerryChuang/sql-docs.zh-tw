---
title: "在 Linux 上的 SQL Server 2017 新功能 |Microsoft 文件"
description: "此主題著重在 Linux 上的 SQL Server 2017 新功能。"
author: rothja
ms.author: jroth
manager: jhubbard
ms.date: 11/28/2017
ms.topic: article
ms.prod: sql-non-specified
ms.prod_service: database-engine
ms.service: 
ms.component: sql-linux
ms.suite: sql
ms.custom: 
ms.technology: database-engine
ms.assetid: 456b6f31-6b97-4e31-80ab-b40151ec4868
ms.workload: On Demand
ms.openlocfilehash: 3e4a3e19fd9d03d3f6e4dd4a68a5a15b922f348d
ms.sourcegitcommit: 531d0245f4b2730fad623a7aa61df1422c255edc
ms.translationtype: MT
ms.contentlocale: zh-TW
ms.lasthandoff: 12/01/2017
---
# <a name="whats-new-for-sql-server-2017-on-linux"></a>在 Linux 上的 SQL Server 2017 新功能

[!INCLUDE[tsql-appliesto-sslinux-only](../includes/tsql-appliesto-sslinux-only.md)]

本文描述在 Linux 上執行的 SQL Server 2017 可用服務的主要功能。

> [!NOTE]
> 除了在本文中的這些功能，在 GA 版本發行後會釋出累積更新。 這些累積更新提供許多改善和修正程式。 如需最新 CU 版本資訊，請參閱[http://aka.ms/sql2017cu](http://aka.ms/sql2017cu)。 如需下載套件和已知的問題，請參閱[版本資訊](sql-server-linux-release-notes.md)。

## <a name="sql-server-database-engine"></a>SQL Server Database Engine

- 啟用核心 SQL Server Database Engine 功能。
- 支援原生 Linux 路徑。
- IPV6 支援。
- 支援 NFS 上資料庫檔案。
- 啟用[透明層級安全性](sql-server-linux-encrypted-connections.md)(TLS) 加密。
- 啟用[Active Directory 驗證](sql-server-linux-active-directory-authentication.md)。
- [可用性群組功能](sql-server-linux-availability-group-overview.md)高可用性。
- [全文檢索搜尋](sql-server-linux-setup-full-text-search.md)支援。

## <a name="sql-server-agent"></a>SQL Server Agent

- 啟用[SQL Server Agent](sql-server-linux-setup-sql-agent.md)支援下列工作：
  - [Transact SQL 作業](sql-server-linux-run-sql-server-agent-job.md)
  - [DB 郵件](sql-server-linux-db-mail-sql-agent.md)
  - [記錄傳送](sql-server-linux-use-log-shipping.md)

## <a name="sql-server-integration-services-ssis"></a>SQL Server Integration Services (SSIS)

- 在 Linux 上執行 SSIS 封裝的功能。 如需詳細資訊，請參閱[ssis conf 與 Linux 上設定 SQL Server Integration Services](sql-server-linux-configure-ssis.md)。

## <a name="other-improvements"></a>其他改進功能

- 命令列組態工具、 [mssql conf](sql-server-linux-configure-mssql-conf.md)。
- 使用自動的安裝支援[環境變數](sql-server-linux-configure-environment-variables.md)。
- 跨平台[Visual Studio Code mssql 伺服器延伸模組](sql-server-linux-develop-use-vscode.md)。
- 跨平台指令碼產生器， [mssql scripter](https://github.com/Microsoft/sql-xplat-cli/blob/dev/doc/usage_guide.md)。
- 跨平台的動態管理檢視 (DMV) 監視， [DBFS 工具](https://github.com/Microsoft/dbfs)。

## <a name="next-steps"></a>後續的步驟

若要安裝 SQL Server on Linux，使用下列教學課程之一：

- [Red Hat Enterprise Linux 上安裝](quickstart-install-connect-red-hat.md)
- [SUSE Linux Enterprise Server 上安裝](quickstart-install-connect-suse.md)
- [在 Ubuntu 上安裝](quickstart-install-connect-ubuntu.md)
- [執行 docker](quickstart-install-connect-docker.md)
- [在 Azure 中佈建 SQL VM](/azure/virtual-machines/linux/sql/provision-sql-server-linux-virtual-machine?toc=%2fsql%2flinux%2ftoc.json)

如需 SQL Server on Linux 其他資訊，請參閱[概觀](sql-server-linux-overview.md)。 如需下載套件不支援的功能和已知的問題清單，請參閱[版本資訊](sql-server-linux-release-notes.md)。

若要查看其他 SQL Server 2017 中導入的增強功能，請參閱[SQL Server 2017 新功能概觀](../sql-server/what-s-new-in-sql-server-2017.md)。

[!INCLUDE[get-help-options](../includes/paragraph-content/get-help-options.md)]
