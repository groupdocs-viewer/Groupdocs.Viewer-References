---
title: LotusNotesViewInfo
second_title: Référence de l'API GroupDocs.Viewer pour .NET
description: Initialise la nouvelle instance deLotusNotesViewInfogroupdocs.viewer.results/lotusnotesviewinfo classe.
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/lotusnotesviewinfo/lotusnotesviewinfo/
---
## LotusNotesViewInfo constructor

Initialise la nouvelle instance de[`LotusNotesViewInfo`](../../lotusnotesviewinfo) classe.

```csharp
public LotusNotesViewInfo(FileType fileType, IList<Page> pages, int notesCount)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fileType | FileType | Le type de fichier. |
| pages | IList`1 | La liste des pages à afficher. |
| notesCount | Int32 | Le nombre de notes contenues dans le fichier de stockage de la base de données Lotus. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*fileType* est nul. |
| ArgumentNullException | Jeté quand*pages* est nul. |
| ArgumentNullException | Jeté quand*notesCount* est nul. |

### Voir également

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* espace de noms [GroupDocs.Viewer.Results](../../lotusnotesviewinfo)
* Assemblée [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->