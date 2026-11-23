---
title: "CadViewInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase CadViewInfogroupdocs.viewer.results/cadviewinfo."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/cadviewinfo/cadviewinfo/
---

## CadViewInfo constructor

Inicializa una nueva instancia de la clase [`CadViewInfo`](../../cadviewinfo).

```csharp
public CadViewInfo(FileType fileType, List<Page> pages, List<Layer> layers, List<Layout> layouts)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileType | FileType | El tipo del archivo. |
| páginas | List`1 | La lista de páginas a visualizar. |
| layers | List`1 | La lista de capas contenidas en el dibujo CAD. |
| layouts | List`1 | La lista de capas contenidas en el dibujo CAD. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *fileType* es nulo. |
| ArgumentNullException | Se lanza cuando *pages* es nulo. |
| ArgumentNullException | Se lanza cuando *layers* es nulo. |
| ArgumentNullException | Se lanza cuando *layouts* es nulo. |

### Ver también

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Page](../../page)
* class [Layer](../../layer)
* class [Layout](../../layout)
* class [CadViewInfo](../../cadviewinfo)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
