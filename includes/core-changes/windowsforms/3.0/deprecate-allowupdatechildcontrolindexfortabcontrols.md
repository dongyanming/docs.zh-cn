---
ms.openlocfilehash: 7e76c32ddeb50eaf1ee93d7cf3cac7469187cc41
ms.sourcegitcommit: 7e2128d4a4c45b4274bea3b8e5760d4694569ca1
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 01/14/2020
ms.locfileid: "75937008"
---
### <a name="allowupdatechildcontrolindexfortabcontrols-compatibility-switch-not-supported"></a>不支持 AllowUpdateChildControlIndexForTabControls 兼容性开关

`Switch.System.Windows.Forms.AllowUpdateChildControlIndexForTabControls` 兼容性开关在 .NET Framework 4.6 及更高版本上的 Windows 窗体中受支持，但在自 .NET Core 3.0 起的 Windows 窗体中不受支持。

#### <a name="change-description"></a>更改描述

在 .NET Framework 4.6 及更高版本中，选中选项卡会对其控件集合重新排序。 借助 `Switch.System.Windows.Forms.AllowUpdateChildControlIndexForTabControls` 兼容性开关，应用程序可在不需要此类重新排序时跳过此行为。

.NET Core 中尚不支持 `Switch.System.Windows.Forms.AllowUpdateChildControlIndexForTabControls` 开关。

#### <a name="version-introduced"></a>引入的版本

3.0 预览版 9

#### <a name="recommended-action"></a>建议操作

删除此开关。 此开关不受支持，且未提供替代功能。

#### <a name="category"></a>类别

Windows 窗体

#### <a name="affected-apis"></a>受影响的 API

- None

<!-- 

### Affected APIs

- Not detectable via API analysis

-->
