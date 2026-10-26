---
title: "GetViewInfo"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Devuelve información sobre la vista y datos específicos del documento."
type: docs
weight: 60
url: /es/net/groupdocs.viewer/viewer/getviewinfo/
---

## GetViewInfo(ViewInfoOptions) {#getviewinfo}

Devuelve información sobre la vista y datos específicos del documento.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewInfoOptions | Las opciones de información de vista. |

### Valor devuelto

Información sobre la vista y datos específicos del documento.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |

### Observaciones

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Ver también

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## GetViewInfo(ViewInfoOptions, CancellationToken) {#getviewinfo_1}

Devuelve información sobre la vista y datos específicos del documento.

```csharp
public ViewInfo GetViewInfo(ViewInfoOptions options, CancellationToken cancellationToken)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewInfoOptions | Las opciones de información de vista. |
| cancellationToken | CancellationToken | Token de cancelación. |

### Valor devuelto

Información sobre la vista y datos específicos del documento.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |

### Observaciones

**Learn more**

* Learn more about document - file type, pages count and other format specific properties: [How to get file information using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Get+file+information)

### Ver también

* class [ViewInfo](../../../groupdocs.viewer.results/viewinfo)
* class [ViewInfoOptions](../../../groupdocs.viewer.options/viewinfooptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
