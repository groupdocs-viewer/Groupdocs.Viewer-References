---
title: TryGetValue
second_title: GroupDocs.Viewer for .NET API 参考
description: 获取与此键关联的条目如果存在
type: docs
weight: 30
url: /zh/net/groupdocs.viewer.caching/icache/trygetvalue/
---
## ICache.TryGetValue&lt;TEntry&gt; method

获取与此键关联的条目（如果存在）。

```csharp
public bool TryGetValue<TEntry>(string key, out TEntry value)
```

| 范围 | 描述 |
| --- | --- |
| TEntry | 输入类型。 |
| key | 标识所请求条目的键。 |
| value | 定位的值或 null。 |

### 返回值

如果找到钥匙。

```csharp
True
```

### 也可以看看

* interface [ICache](../../icache)
* 命名空间 [GroupDocs.Viewer.Caching](../../icache)
* 部件 [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
