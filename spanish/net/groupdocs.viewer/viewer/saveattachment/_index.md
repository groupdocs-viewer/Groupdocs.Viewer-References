---
title: "SaveAttachment"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Guarda el archivo adjunto en el flujo de destino."
type: docs
weight: 70
url: /es/net/groupdocs.viewer/viewer/saveattachment/
---

## SaveAttachment(Attachment, Stream, CancellationToken) {#saveattachment_1}

Guarda el archivo adjunto en el flujo *destino*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination, 
    CancellationToken cancellationToken)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| adjunto | Attachment | El adjunto. |
| destino | Flujo | El flujo de escritura. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *attachment* es nulo. |
| ArgumentNullException | Lanzado cuando *destination* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

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

## SaveAttachment(Attachment, Stream) {#saveattachment}

Guarda el archivo adjunto en el flujo *destino*.

```csharp
public void SaveAttachment(Attachment attachment, Stream destination)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| adjunto | Attachment | El adjunto. |
| destino | Flujo | El flujo de escritura. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *attachment* es nulo. |
| ArgumentNullException | Lanzado cuando *destination* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

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
