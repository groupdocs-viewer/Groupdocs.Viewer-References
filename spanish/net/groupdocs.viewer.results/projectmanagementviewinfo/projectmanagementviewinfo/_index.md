---
title: "ProjectManagementViewInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase ProjectManagementViewInfogroupdocs.viewer.results/projectmanagementviewinfo."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/projectmanagementviewinfo/projectmanagementviewinfo/
---

## ProjectManagementViewInfo() {#constructor}

Inicializa una nueva instancia de la clase [`ProjectManagementViewInfo`](../../projectmanagementviewinfo).

```csharp
public ProjectManagementViewInfo()
```

### Ver también

* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## ProjectManagementViewInfo(FileType, List&lt;Page&gt;, DateTime, DateTime) {#constructor_1}

Inicializa una nueva instancia de la clase [`ProjectManagementViewInfo`](../../projectmanagementviewinfo).

```csharp
public ProjectManagementViewInfo(FileType fileType, List<Page> pages, DateTime startDate, 
    DateTime endDate)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileType | FileType | El tipo del archivo. |
| páginas | List`1 | La lista de páginas a visualizar. |
| startDate | DateTime | La fecha y hora en que el proyecto comenzó. |
| endDate | DateTime | La fecha y hora en que se debe completar el proyecto. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *fileType* es nulo. |
| ArgumentNullException | Se lanza cuando *pages* es nulo. |

### Ver también

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [ProjectManagementViewInfo](../../projectmanagementviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
