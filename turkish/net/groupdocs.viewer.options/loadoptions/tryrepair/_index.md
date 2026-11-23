---
title: "TryRepair"
second_title: "GroupDocs.Viewer için .NET API Referansı"
description: "Etkinleştirildiğinde, GroupDocs.Viewer PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer false'tur."
type: docs
weight: 80
url: /tr/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Etkinleştirildiğinde GroupDocs.Viewer, PDF belgelerindeki yapısal bozulmaları onarmaya çalışır. Varsayılan değer `false`.

```csharp
public bool TryRepair { get; set; }
```

### Açıklamalar

Bu özellik, bir PDF belgesindeki aşağıdaki sorunları ele alır:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### Ayrıca Bakınız

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Viewer.dll için oluşturuldu -->
