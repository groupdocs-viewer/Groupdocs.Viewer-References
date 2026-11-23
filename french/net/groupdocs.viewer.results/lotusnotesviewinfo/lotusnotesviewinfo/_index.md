---
title: "LotusNotesViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe LotusNotesViewInfogroupdocs.viewer.results/lotusnotesviewinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/lotusnotesviewinfo/lotusnotesviewinfo/
---

## LotusNotesViewInfo() {#constructor}

Initialise une nouvelle instance de la classe [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo()
```

### Voir aussi

* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## LotusNotesViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Initialise une nouvelle instance de la classe [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | List`1 | La liste des pages à afficher. |
| notesCount | Int32 | Le nombre de notes contenu dans le fichier de stockage de la base de données Lotus. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *pages* est nul. |
| ArgumentNullException | Lancée lorsque *notesCount* est null. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
