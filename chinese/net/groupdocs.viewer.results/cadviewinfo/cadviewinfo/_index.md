---
title: CadViewInfo
second_title: GroupDocs.Viewer for .NET API 参考
description: 初始化的新实例CadViewInfogroupdocs.viewer.results/cadviewinfo类.
type: docs
weight: 10
url: /zh/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---
## CadViewInfo constructor

初始化的新实例[`CadViewInfo`](../../cadviewinfo)类.

```csharp
public CadViewInfo(FileType fileType, IList<Page> pages, IList<Layer> layers, IList<Layout> layouts)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fileType | FileType | 文件的类型。 |
| pages | IList`1 | 要查看的页面列表。 |
| layers | IList`1 | CAD 绘图所包含的图层列表。 |
| layouts | IList`1 | CAD 绘图所包含的图层列表。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentNullException | 何时抛出*fileType*一片空白。 |
| ArgumentNullException | 何时抛出*pages*一片空白。 |
| ArgumentNullException | 何时抛出*layers*一片空白。 |
| ArgumentNullException | 何时抛出*layouts*一片空白。 |

### 也可以看看

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* 命名空间 [GroupDocs.Viewer.Results](../../cadviewinfo)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
