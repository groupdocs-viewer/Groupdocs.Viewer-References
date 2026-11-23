---
title: "Viewer"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Representa la clase principal que controla el proceso de renderizado del documento."
type: docs
weight: 50
url: /es/net/groupdocs.viewer/viewer/
---

## Viewer class

Representa la clase principal que controla el proceso de renderizado del documento.

```csharp
public class Viewer : IDisposable
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Viewer](viewer#constructor)(Func&lt;Stream&gt;) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_4)(Stream) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_12)(string) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_2)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_1)(Func&lt;Stream&gt;, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_5)(Stream, bool) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_6)(Stream, LoadOptions) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_10)(Stream, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_13)(string, LoadOptions) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_15)(string, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_7)(Stream, LoadOptions, bool) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_8)(Stream, LoadOptions, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_11)(Stream, ViewerSettings, bool) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_14)(string, LoadOptions, ViewerSettings) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |
| [Viewer](viewer#constructor_9)(Stream, LoadOptions, ViewerSettings, bool) | Inicializa una nueva instancia de la clase [`Viewer`](../viewer). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../groupdocs.viewer/viewer/dispose)() | Libera el flujo de archivo y los recursos internos administrados. |
| [GetAllFonts](../../groupdocs.viewer/viewer/getallfonts)() | Devuelve todas las fuentes, usadas en los documentos cargados, incluidas aquellas que están incrustadas dentro del propio documento y las fuentes del sistema que están instaladas en el SO y se usan en el documento. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments)() | Devuelve los archivos adjuntos contenidos en el documento. |
| [GetAttachments](../../groupdocs.viewer/viewer/getattachments#getattachments_1)(CancellationToken) | Devuelve los archivos adjuntos contenidos en el documento. |
| [GetFileInfo](../../groupdocs.viewer/viewer/getfileinfo)() | Devuelve información sobre el archivo, como el tipo de archivo y una bandera que indica si el archivo está encriptado. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo)(ViewInfoOptions) | Devuelve información sobre la vista y datos específicos del documento. |
| [GetViewInfo](../../groupdocs.viewer/viewer/getviewinfo#getviewinfo_1)(ViewInfoOptions, CancellationToken) | Devuelve información sobre la vista y datos específicos del documento. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment)(Attachment, Stream) | Guarda el archivo adjunto en el flujo *destino*. |
| [SaveAttachment](../../groupdocs.viewer/viewer/saveattachment#saveattachment_1)(Attachment, Stream, CancellationToken) | Guarda el archivo adjunto en el flujo *destino*. |
| [Search](../../groupdocs.viewer/viewer/search)(SearchHighlightOptions) | Realiza una búsqueda de texto y su resaltado (si se encuentra) en el documento cargado según las opciones cargadas. |
| [View](../../groupdocs.viewer/viewer/view#view)(ViewOptions) | Crea una vista de todas las páginas del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_2)(ViewOptions, CancellationToken) | Crea una vista de todas las páginas del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_1)(ViewOptions, params int[]) | Crea una vista de páginas específicas del documento. |
| [View](../../groupdocs.viewer/viewer/view#view_3)(ViewOptions, CancellationToken, params int[]) | Crea una vista de páginas específicas del documento. |

### Ver también

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
