---
title: "Attachment"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa el archivo adjunto contenido en el archivo PDF de archivo de mensajes de correo electrónico o en el archivo de datos de Outlook."
type: docs
weight: 80
url: /es/net/groupdocs.viewer.results/attachment/
---

## Attachment class

Representa el archivo adjunto contenido en un mensaje de correo electrónico, archivo comprimido, documento PDF o archivo de datos de Outlook.

```csharp
public class Attachment
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Attachment](attachment#constructor)() | Inicializa una nueva instancia de la clase [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_1)(string, string) | Inicializa una nueva instancia de la clase [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_3)(string, string, string, long) | Inicializa una nueva instancia de la clase [`Attachment`](../attachment). |
| [Attachment](attachment#constructor_2)(string, string, string, FileType, long) | Inicializa una nueva instancia de la clase [`Attachment`](../attachment). |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [FileName](../../groupdocs.viewer.results/attachment/filename) { get; set; } | Nombre de archivo del adjunto. |
| [FilePath](../../groupdocs.viewer.results/attachment/filepath) { get; set; } | Ruta relativa del adjunto, p.ej. carpeta/archivo.docx o nombre de archivo cuando el archivo está ubicado en la raíz de un archivo comprimido, en un mensaje de correo electrónico o archivo de datos. |
| [FileType](../../groupdocs.viewer.results/attachment/filetype) { get; set; } | Tipo de archivo del adjunto. |
| [Id](../../groupdocs.viewer.results/attachment/id) { get; set; } | Identificador único del adjunto en el contexto de un solo archivo que contiene este adjunto. |
| [Size](../../groupdocs.viewer.results/attachment/size) { get; set; } | Tamaño del archivo del adjunto en bytes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../groupdocs.viewer.results/attachment/tostring)() | Devuelve una cadena que representa el objeto actual. |

### Ver también

* namespace [GroupDocs.Viewer.Results](../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
