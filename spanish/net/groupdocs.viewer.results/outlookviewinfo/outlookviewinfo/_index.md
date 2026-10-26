---
title: "OutlookViewInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase OutlookViewInfogroupdocs.viewer.results/outlookviewinfo."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/outlookviewinfo/outlookviewinfo/
---

## OutlookViewInfo() {#constructor}

Inicializa una nueva instancia de la clase [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo()
```

### Ver también

* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## OutlookViewInfo(FileType, List&lt;Page&gt;, List&lt;string&gt;) {#constructor_1}

Inicializa una nueva instancia de la clase [`OutlookViewInfo`](../../outlookviewinfo).

```csharp
public OutlookViewInfo(FileType fileType, List<Page> pages, List<string> folders)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileType | FileType | El tipo del archivo. |
| páginas | List`1 | La lista de páginas a visualizar. |
| carpetas | List`1 | La lista de carpetas contenidas en el archivo de datos de Outlook. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *fileType* es nulo. |
| ArgumentNullException | Se lanza cuando *pages* es nulo. |
| ArgumentNullException | Lanzado cuando *folders* es nulo. |

### Ver también

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [OutlookViewInfo](../../outlookviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
