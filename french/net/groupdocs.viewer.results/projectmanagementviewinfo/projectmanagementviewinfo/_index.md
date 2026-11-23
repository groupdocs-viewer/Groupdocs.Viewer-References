---
title: "ProjectManagementViewInfo"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo classe."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

Initialise une nouvelle instance de [`ProjectManagementViewInfo`](../../projectmanagementviewinfo) classe.

```csharp
public ProjectManagementViewInfo()
```

### Voir aussi

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

Initialise une nouvelle instance de [`ProjectManagementViewInfo`](../../projectmanagementviewinfo) classe.

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileType | FileType | Le type du fichier. |
| pages | List`1 | La liste des pages à afficher. |
| startDate | DateTime | La date et l'heure à partir desquelles le projet a commencé. |
| endDate | DateTime | La date et l'heure auxquelles le projet doit être terminé. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *fileType* est nul. |
| ArgumentNullException | Lancée lorsque *pages* est nul. |

### Voir aussi

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
