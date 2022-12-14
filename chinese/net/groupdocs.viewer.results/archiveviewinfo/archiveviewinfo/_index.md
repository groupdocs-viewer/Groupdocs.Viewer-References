---
title: ArchiveViewInfo
second_title: GroupDocs.Viewer for .NET API 参考
description: 初始化的新实例ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo类.
type: docs
weight: 10
url: /zh/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---
## ArchiveViewInfo constructor

初始化的新实例[`ArchiveViewInfo`](../../archiveviewinfo)类.

```csharp
public ArchiveViewInfo(FileType fileType, IList<Page> pages, IList<string> folders)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 文件的类型。 |
| pages | IList`1 | 要查看的页面列表。 |
| folders | IList`1 | 存档文件包含的文件夹列表。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*fileType*一片空白。 |
| ArgumentNullException | 何时抛出*pages*一片空白。 |
| ArgumentNullException | 何时抛出*folders*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* 命名空间 [GroupDocs.Viewer.Results](../../archiveviewinfo)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
