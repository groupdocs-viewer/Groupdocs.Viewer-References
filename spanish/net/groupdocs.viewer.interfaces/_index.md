---
title: "GroupDocs.Viewer.Interfaces"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "El espacio de nombres proporciona interfaces para instanciar y liberar el documento de salida y sus recursos."
type: docs
weight: 60
url: /es/net/groupdocs.viewer.interfaces/
---

El espacio de nombres proporciona interfaces para instanciar y liberar el documento de salida y sus recursos.

## Clases

| Clase | Descripción |
| --- | --- |
| [CreateFileStream](./createfilestream) | Representa el método que instancia el flujo utilizado para escribir los datos del archivo de salida. |
| [CreatePageStream](./createpagestream) | Representa el método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| [CreateResourceStream](./createresourcestream) | Representa el método que instancia el flujo utilizado para escribir los datos del recurso HTML de salida. |
| [CreateResourceUrl](./createresourceurl) | Representa el método que crea la URL para el recurso HTML. |
| [ReleaseFileStream](./releasefilestream) | Libera el flujo que fue instanciado por el método asociado al delegado [`CreateFileStream`](../groupdocs.viewer.interfaces/createfilestream). |
| [ReleasePageStream](./releasepagestream) | Libera el flujo que fue instanciado por el método asociado al delegado [`CreatePageStream`](../groupdocs.viewer.interfaces/createpagestream). |
| [ReleaseResourceStream](./releaseresourcestream) | Libera el flujo que fue instanciado por el método asociado al delegado [`CreateResourceStream`](../groupdocs.viewer.interfaces/createresourcestream). |
## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [IFileStreamFactory](./ifilestreamfactory) | Define los métodos necesarios para instanciar y liberar el flujo de archivo de salida. |
| [IPageStreamFactory](./ipagestreamfactory) | Define los métodos necesarios para instanciar y liberar el flujo de página de salida. |
| [IResourceStreamFactory](./iresourcestreamfactory) | Define los métodos necesarios para crear la URL del recurso, instanciar y liberar el flujo del recurso HTML de salida. |

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
