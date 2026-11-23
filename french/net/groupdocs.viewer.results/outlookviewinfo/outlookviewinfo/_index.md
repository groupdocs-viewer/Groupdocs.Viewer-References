---
title: "OutlookViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe OutlookViewInfogroupdocs.viewer.results/outlookviewinfo."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

Initialise une nouvelle instance de la classe [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo()
```

### Voir aussi

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | List`1 | La liste des pages à afficher. |
| dossiers | List`1 | La liste des dossiers contenus par le fichier de données Outlook. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *pages* est nul. |
| ArgumentNullException | Lancé lorsque *folders* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
