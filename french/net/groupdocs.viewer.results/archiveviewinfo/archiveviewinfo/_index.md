---
title: "ArchiveViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe ArchiveViewInfogroupdocs.viewer.results/archiveviewinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/archiveviewinfo/archiveviewinfo/
---

## ArchiveViewInfo() {#constructor}

Initialise une nouvelle instance de la classe [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo()
```

### Voir aussi

* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ArchiveViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe [`ArchiveViewInfo`](../../archiveviewinfo).

```csharp
public ArchiveViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | List`1 | La liste des pages à afficher. |
| dossiers | List`1 | La liste des dossiers contenus dans le fichier d'archive. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *pages* est nul. |
| ArgumentNullException | Lancé lorsque *folders* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ArchiveViewInfo](../../archiveviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
