---
title: "GetAttachments"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve los archivos adjuntos contenidos en el documento."
type: docs
weight: 40
url: /es/net/groupdocs.viewer/viewer/getattachments/
---

## GetAttachments() {#getattachments}

Devuelve los archivos adjuntos contenidos en el documento.

```csharp
public IList<Attachment> GetAttachments()
```

### Valor devuelto

Adjuntos contenidos en el documento.

### Excepciones

| excepción | condición |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |

### Observaciones

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Ver también

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetAttachments(CancellationToken) {#getattachments_1}

Devuelve los archivos adjuntos contenidos en el documento.

```csharp
public IList<Attachment> GetAttachments(CancellationToken cancellationToken)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor devuelto

Adjuntos contenidos en el documento.

### Excepciones

| excepción | condición |
| --- | --- |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |

### Observaciones

**Learn more**

* Learn more about getting document attachments in C#: [How to get list of document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+attachments)
* Learn more about saving document attachments in C#: [How to save document attachments using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Save+attachments)

### Ver también

* class [Attachment](../../../groupdocs.viewer.results/attachment)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
