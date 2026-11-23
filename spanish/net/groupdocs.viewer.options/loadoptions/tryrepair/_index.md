---
title: "TryRepair"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. El valor predeterminado es false."
type: docs
weight: 80
url: /es/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Cuando está habilitado, GroupDocs.Viewer intenta reparar la corrupción estructural en documentos PDF. El valor predeterminado es `false`.

```csharp
public bool TryRepair { get; set; }
```

### Observaciones

Esta característica aborda los siguientes problemas en un documento PDF:

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### Ver también

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
