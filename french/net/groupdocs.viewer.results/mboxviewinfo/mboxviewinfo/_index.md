---
title: "MboxViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe MboxViewInfogroupdocs.viewer.results/mboxviewinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/mboxviewinfo/mboxviewinfo/
---

## MboxViewInfo() {#constructor}

Initialise une nouvelle instance de la classe [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo()
```

### Voir aussi

* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## MboxViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Initialise une nouvelle instance de la classe [`MboxViewInfo`](../../mboxviewinfo).

```csharp
public MboxViewInfo(FileType fileType, List<Page> pages, int notesCount)
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
* class [MboxViewInfo](../../mboxviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
