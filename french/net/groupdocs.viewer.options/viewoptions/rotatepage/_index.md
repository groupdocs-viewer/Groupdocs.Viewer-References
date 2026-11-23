---
title: "RotatePage"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Applique la rotation horaire à une page."
type: docs
weight: 30
url: /fr/net/groupdocs.viewer.options/viewoptions/rotatepage/
---

## ViewOptions.RotatePage method

Applique la rotation horaire à une page.

```csharp
public void RotatePage(int pageNumber, Rotation rotation)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Le numéro de page doit être strictement supérieur à 0. |
| rotation | Rotation | La valeur de rotation. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentOutOfRangeException | Lancée lorsque *pageNumber* est inférieur ou égal à zéro. |
| ArgumentException | Lancée lorsque la rotation pour la page numéro *pageNumber* a déjà été ajoutée. |

### Remarques

Pour plus de détails, voir la [documentation](https://docs.groupdocs.com/viewer/net/flip-or-rotate-pages/).

### Voir aussi

* enum [Rotation](../../rotation)
* class [ViewOptions](../../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
