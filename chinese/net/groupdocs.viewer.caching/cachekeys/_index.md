---
title: CacheKeys
second_title: GroupDocs.Viewer for .NET API 参考
description: 提供检索缓存条目唯一标识符的方法
type: docs
weight: 10
url: /zh/net/groupdocs.viewer.caching/cachekeys/
---
## CacheKeys class

提供检索缓存条目唯一标识符的方法。

```csharp
public static class CacheKeys
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetAttachmentKey](../../groupdocs.viewer.caching/cachekeys/getattachmentkey)(string) | 返回代表附件文件的缓存条目的唯一标识符。 |
| static [GetAttachmentsKey](../../groupdocs.viewer.caching/cachekeys/getattachmentskey)() | 返回表示集合的缓存条目的唯一标识符[`Attachment`](../../groupdocs.viewer.results/attachment)对象. |
| static [GetFileInfoKey](../../groupdocs.viewer.caching/cachekeys/getfileinfokey)() | 返回代表缓存条目的唯一标识符[`ViewInfo`](../../groupdocs.viewer.results/viewinfo)对象. |
| static [GetFileKey](../../groupdocs.viewer.caching/cachekeys/getfilekey)(string) | 返回代表文件的缓存条目的唯一标识符。 |
| static [GetPageKey](../../groupdocs.viewer.caching/cachekeys/getpagekey)(int, string) | 返回代表页面文件的缓存条目的唯一标识符。 |
| static [GetResourceFilter](../../groupdocs.viewer.caching/cachekeys/getresourcefilter)(int) | 返回过滤器字符串以搜索表示[`Resource`](../../groupdocs.viewer.results/resource)对象. |
| static [GetResourceKey](../../groupdocs.viewer.caching/cachekeys/getresourcekey)(int, Resource) | 返回代表缓存条目的唯一标识符[`Resource`](../../groupdocs.viewer.results/resource)对象. |
| static [GetViewInfoKey](../../groupdocs.viewer.caching/cachekeys/getviewinfokey)() | 返回代表缓存条目的唯一标识符[`ViewInfo`](../../groupdocs.viewer.results/viewinfo)对象. |

### 也可以看看

* 命名空间 [GroupDocs.Viewer.Caching](../../groupdocs.viewer.caching)
* 部件 [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
