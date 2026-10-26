---
title: "Attachment"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase Attachmentgroupdocs.viewer.results/attachment."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.results/attachment/attachment/
---

## Attachment() {#constructor}

Inicializa una nueva instancia de la clase [`Attachment`](../../attachment).

```csharp
public Attachment()
```

### Ver también

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string) {#constructor_1}

Inicializa una nueva instancia de la clase [`Attachment`](../../attachment).

```csharp
public Attachment(string fileName, string filePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileName | String | Nombre de archivo del adjunto. |
| filePath | String | Ruta relativa del adjunto, p.ej. carpeta/archivo.docx o nombre de archivo cuando el archivo está ubicado en la raíz de un archivo comprimido, en un mensaje de correo electrónico o archivo de datos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *fileName* es nulo o está vacío. |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |

### Ver también

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, long) {#constructor_3}

Inicializa una nueva instancia de la clase [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, long size)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| id | String | Identificador único (en el contexto de un solo archivo) del adjunto. |
| fileName | String | Nombre de archivo del adjunto. |
| filePath | String | Ruta relativa del adjunto, p.ej. carpeta/archivo.docx o nombre de archivo cuando el archivo está ubicado en la raíz de un archivo comprimido, en un mensaje de correo electrónico o archivo de datos. |
| tamaño | Int64 | Tamaño del archivo del adjunto en bytes. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *id* es nulo o está vacío. |
| ArgumentException | Se lanza cuando *fileName* es nulo o está vacío. |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |

### Ver también

* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Attachment(string, string, string, FileType, long) {#constructor_2}

Inicializa una nueva instancia de la clase [`Attachment`](../../attachment).

```csharp
public Attachment(string id, string fileName, string filePath, FileType fileType, long size)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| id | String | Identificador único (en el contexto de un solo archivo) del adjunto. |
| fileName | String | Nombre de archivo del adjunto. |
| filePath | String | Ruta relativa del adjunto, p.ej. carpeta/archivo.docx o nombre de archivo cuando el archivo está ubicado en la raíz de un archivo comprimido, en un mensaje de correo electrónico o archivo de datos. |
| fileType | FileType | Tipo de archivo del adjunto. |
| tamaño | Int64 | Tamaño del archivo del adjunto en bytes. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *id* es nulo o está vacío. |
| ArgumentException | Se lanza cuando *fileName* es nulo o está vacío. |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |
| ArgumentNullException | Se lanza cuando *fileType* es nulo. |

### Ver también

* class [FileType](../../../groupdocs.viewer/filetype)
* class [Attachment](../../attachment)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
