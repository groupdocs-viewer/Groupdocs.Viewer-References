---
title: View
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Crea una vista de todas las páginas del documento.
type: docs
weight: 70
url: /es/net/groupdocs.viewer/viewer/view/
---
## View(ViewOptions) {#view}

Crea una vista de todas las páginas del documento.

```csharp
public void View(ViewOptions options)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | ViewOptions | Las opciones de visualización. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Se lanza cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Se lanza cuando la contraseña que se especificó es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el archivo adjunto. |

### Observaciones

**Aprende más**

* Más información sobre las diferentes opciones de visualización siguiendo esta guía: [Cómo personalizar la salida de visualización de documentos usando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken) {#view_2}

Crea una vista de todas las páginas del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | ViewOptions | Las opciones de visualización. |
| cancellationToken | CancellationToken | Token de cancelación para enviar una solicitud para cancelar el proceso de visualización actual. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*options* es nulo. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Se lanza cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Se lanza cuando la contraseña que se especificó es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el archivo adjunto. |

### Observaciones

**Aprende más**

* Más información sobre las diferentes opciones de visualización siguiendo esta guía: [Cómo personalizar la salida de visualización de documentos usando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, params int[]) {#view_1}

Crea una vista de páginas específicas del documento.

```csharp
public void View(ViewOptions options, params int[] pageNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | ViewOptions | Las opciones de visualización. |
| pageNumbers | Int32[] | Los números de página para ver. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*options* es nulo. |
| ArgumentNullException | arrojado cuando*pageNumbers* es nulo. |
| ArgumentException | arrojado cuando*pageNumbers* esta vacio. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Se lanza cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Se lanza cuando la contraseña que se especificó es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el archivo adjunto. |

### Observaciones

**Aprende más**

* Más información sobre las diferentes opciones de visualización siguiendo esta guía: [Cómo personalizar la salida de visualización de documentos usando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## View(ViewOptions, CancellationToken, params int[]) {#view_3}

Crea una vista de páginas específicas del documento.

```csharp
public void View(ViewOptions options, CancellationToken cancellationToken, params int[] pageNumbers)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| options | ViewOptions | Las opciones de visualización. |
| pageNumbers | CancellationToken | Los números de página para ver. |
| cancellationToken | Int32[] | Token de cancelación para cancelar el procesamiento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*options* es nulo. |
| ArgumentNullException | arrojado cuando*pageNumbers* es nulo. |
| ArgumentException | arrojado cuando*pageNumbers* esta vacio. |
| [PasswordRequiredException](../../../groupdocs.viewer.exceptions/passwordrequiredexception) | Se lanza cuando se requiere una contraseña para abrir el documento. |
| [IncorrectPasswordException](../../../groupdocs.viewer.exceptions/incorrectpasswordexception) | Se lanza cuando la contraseña que se especificó es incorrecta. |
| [GroupDocsViewerException](../../../groupdocs.viewer.exceptions/groupdocsviewerexception) | Lanzado cuando no se pudo encontrar el archivo adjunto. |

### Observaciones

**Aprende más**

* Más información sobre las diferentes opciones de visualización siguiendo esta guía: [Cómo personalizar la salida de visualización de documentos usando GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Viewing)

### Ver también

* class [ViewOptions](../../../groupdocs.viewer.options/viewoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
