---
title: "Vista"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Crea una vista de todas las páginas del documento."
type: docs
weight: 90
url: /es/net/groupdocs.viewer/viewer/view/
---

## View(ViewOptions) {#view}

Crea una vista de todas las páginas del documento.

```csharp
public void View(ViewOptions options)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewOptions | Las opciones de vista. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

### Observaciones

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crea una vista de todas las páginas del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewOptions | Las opciones de vista. |
| cancellationToken | CancellationToken | Token de cancelación para enviar una solicitud que cancele el proceso de vista actual. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

### Observaciones

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crea una vista de páginas específicas del documento.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewOptions | Las opciones de vista. |
| pageNumbers | Int32[] | Los números de página para ver. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| ArgumentNullException | Lanzado cuando *pageNumbers* es nulo. |
| ArgumentException | Lanzado cuando *pageNumbers* está vacío. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

### Observaciones

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crea una vista de páginas específicas del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| opciones | ViewOptions | Las opciones de vista. |
| pageNumbers | CancellationToken | Los números de página para ver. |
| cancellationToken | Int32[] | Token de cancelación para cancelar el procesamiento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *options* es nulo. |
| ArgumentNullException | Lanzado cuando *pageNumbers* es nulo. |
| ArgumentException | Lanzado cuando *pageNumbers* está vacío. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Lanzado cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Lanzado cuando la contraseña especificada es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el adjunto. |

### Observaciones

**Learn more**

* More about different viewing options following this guide: [How to customize document viewing output using GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
