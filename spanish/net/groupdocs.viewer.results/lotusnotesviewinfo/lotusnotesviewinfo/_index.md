---
title: "LotusNotesViewInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase LotusNotesViewInfogroupdocs.viewer.results/lotusnotesviewinfo."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/lotusnotesviewinfo/lotusnotesviewinfo/
---

## LotusNotesViewInfo() {#constructor}

Inicializa una nueva instancia de la clase [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo()
```

### Ver también

* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## LotusNotesViewInfo(FileType, List&lt;Page&gt;, int) {#constructor_1}

Inicializa una nueva instancia de la clase [`LotusNotesViewInfo`](../../lotusnotesviewinfo).

```csharp
public LotusNotesViewInfo(FileType fileType, List<Page> pages, int notesCount)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileType | FileType | El tipo del archivo. |
| páginas | List`1 | La lista de páginas a visualizar. |
| notesCount | Int32 | El número de notas contenido en el archivo de almacenamiento de la base de datos Lotus. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *fileType* es nulo. |
| ArgumentNullException | Se lanza cuando *pages* es nulo. |
| ArgumentNullException | Se lanza cuando *notesCount* es nulo. |

### Ver también

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [LotusNotesViewInfo](../../lotusnotesviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
