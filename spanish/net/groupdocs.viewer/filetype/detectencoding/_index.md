---
title: "DetectEncoding"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Intenta detectar la codificación de archivos de texto TXTgroupdocs.viewer/filetype/txt TSVgroupdocs.viewer/filetype/tsv y CSVgroupdocs.viewer/filetype/csv por ruta."
type: docs
weight: 2060
url: /es/net/groupdocs.viewer/filetype/detectencoding/
---

## DetectEncoding(string) {#detectencoding_1}

Intenta detectar la codificación de archivos de texto [`TXT`](../txt), [`TSV`](../tsv) y [`CSV`](../csv) por ruta.

```csharp
public static Encoding DetectEncoding(string filePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | El nombre del archivo o la ruta del archivo. |

### Valor devuelto

Codificación o null cuando falla la detección de la codificación de un archivo.

### Ejemplos

El ejemplo muestra cómo detectar la codificación de un archivo de texto.

```csharp
Encoding encoding = FileType.DetectEncoding("message.txt");
```

### Ver también

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## DetectEncoding(Stream) {#detectencoding}

Intenta detectar la codificación de archivos de texto [`TXT`](../txt), [`TSV`](../tsv) y [`CSV`](../csv) por flujo.

```csharp
public static Encoding DetectEncoding(Stream stream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |

### Valor devuelto

Codificación o null cuando falla la detección de la codificación de un archivo.

### Ejemplos

El ejemplo muestra cómo detectar la codificación de un archivo de texto.

```csharp
Stream stream = File.OpenRead("message.txt");
Encoding encoding = FileType.DetectEncoding(stream);
```

### Ver también

* class [FileType](../../filetype)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
