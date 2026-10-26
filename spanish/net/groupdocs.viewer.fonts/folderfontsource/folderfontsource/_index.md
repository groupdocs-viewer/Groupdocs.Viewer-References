---
title: "FolderFontSource"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase FolderFontSourcegroupdocs.viewer.fonts/folderfontsource."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.fonts/folderfontsource/folderfontsource/
---

## FolderFontSource constructor

Inicializa una nueva instancia de la clase [`FolderFontSource`](../../folderfontsource).

```csharp
public FolderFontSource(string folderPath, SearchOption searchOption)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| folderPath | String | Ruta a la carpeta que contiene fuentes TrueType. |
| searchOption | SearchOption | Especifica si se debe buscar en la carpeta actual, o en la carpeta actual y todas sus subcarpetas. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *folderPath* es nulo. |
| DirectoryNotFoundException | Se lanza cuando la ruta especificada en *folderPath* no se puede localizar. |

### Ver también

* enum [SearchOption](../../searchoption)
* class [FolderFontSource](../../folderfontsource)
* namespace [GroupDocs.Viewer.Fonts](../../../groupdocs.viewer.fonts)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
