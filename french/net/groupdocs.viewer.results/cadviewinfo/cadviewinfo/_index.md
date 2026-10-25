---
title: "CadViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe CadViewInfogroupdocs.viewer.results/cadviewinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

Initialise une nouvelle instance de la classe [`CadViewInfo`](../../cadviewinfo).

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | List`1 | La liste des pages à afficher. |
| layers | List`1 | La liste des calques contenus dans le dessin CAD. |
| layouts | List`1 | La liste des calques contenus dans le dessin CAD. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *pages* est nul. |
| ArgumentNullException | Lancée lorsque *layers* est null. |
| ArgumentNullException | Lancée lorsque *layouts* est null. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
