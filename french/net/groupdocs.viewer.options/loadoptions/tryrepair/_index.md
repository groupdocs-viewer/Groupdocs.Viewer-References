---
title: "TryRepair"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Lorsque activé, GroupDocs.Viewer tente de réparer les corruptions structurelles des documents PDF. La valeur par défaut est false."
type: docs
weight: 80
url: /fr/net/groupdocs.viewer.options/loadoptions/tryrepair/
---

## LoadOptions.TryRepair property

Lorsqu'il est activé, GroupDocs.Viewer tente de réparer les corruptions structurelles dans les documents PDF. La valeur par défaut est `false`.

```csharp
public bool TryRepair { get; set; }
```

### Remarques

Cette fonctionnalité résout les problèmes suivants dans un document PDF :

* Broken references within the document (incorrect object offsets in the Cross-reference list).
* Missing critical elements like root object, page object, or page content.
* Circular references (Form X-object referencing itself).

### Voir aussi

* class [LoadOptions](../../loadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
