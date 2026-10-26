---
title: "IAuxDisposable"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Amplía la interfaz estándar IDisposable y permite obtener el estado actual de un objeto y suscribirse al evento de eliminación."
type: docs
weight: 20
url: /es/net/groupdocs.viewer/iauxdisposable/
---

## IAuxDisposable interface

Amplía la interfaz estándar IDisposable, permite obtener el estado actual de un objeto y suscribirse al evento de disposición.

```csharp
public interface IAuxDisposable : IDisposable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [IsDisposed](../../groupdocs.viewer/iauxdisposable/isdisposed) { get; } | Indica si un recurso ya está eliminado (`true`) o no (`false`). |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [Disposed](../../groupdocs.viewer/iauxdisposable/disposed) | Ocurre cuando el objeto se elimina, justo después de que la eliminación de los recursos se completa con éxito. |

### Ver también

* namespace [GroupDocs.Viewer](../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
