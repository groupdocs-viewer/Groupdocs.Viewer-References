---
title: "com.groupdocs.viewer.interfaces"
second_title: "Referencia de API de GroupDocs.Viewer para Node.js vía Java"
description: "El paquete proporciona interfaces para instanciar y liberar el documento de salida y sus recursos."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.viewer.interfaces/
---

El paquete proporciona interfaces para instanciar y liberar el documento de salida y sus recursos.

Estas interfaces se utilizan para gestionar la creación y liberación de flujos y URL asociados con el archivo de salida, páginas y recursos HTML.

Las principales interfaces en este paquete son:

 *  [CreateFileStream](../../com.groupdocs.viewer.interfaces/createfilestream) - Represents an interface for instantiating a stream used to write output file data.
 *  [FileStreamFactory](../../com.groupdocs.viewer.interfaces/filestreamfactory) - Defines methods for instantiating and releasing the output file stream.
 *  [ReleasePageStream](../../com.groupdocs.viewer.interfaces/releasepagestream) - Releases a stream that was instantiated by a method associated with the CreatePageStream interface.

Para obtener más detalles sobre cómo trabajar con estas interfaces y personalizar el manejo del documento de salida y los recursos en GroupDocs.Viewer, consulte la [GroupDocs.Viewer Documentation][].


[GroupDocs.Viewer Documentation]: https://docs.groupdocs.com/viewer/java/


## Interfaces

| Interfaz | Descripción |
| --- | --- |
| [CreateFileStream](../com.groupdocs.viewer.interfaces/createfilestream) | Representa una interfaz que instancia un flujo utilizado para escribir los datos del archivo de salida. |
| [CreatePageStream](../com.groupdocs.viewer.interfaces/createpagestream) | Representa una interfaz que instancia un flujo utilizado para escribir los datos de la página de salida. |
| [CreateResourceStream](../com.groupdocs.viewer.interfaces/createresourcestream) | Representa una interfaz que instancia un flujo utilizado para escribir los datos del recurso HTML de salida. |
| [CreateResourceUrl](../com.groupdocs.viewer.interfaces/createresourceurl) | Representa una interfaz que crea una URL para un recurso HTML. |
| [FileReader](../com.groupdocs.viewer.interfaces/filereader) | Declara una interfaz para leer un flujo de archivo. |
| [FileStreamFactory](../com.groupdocs.viewer.interfaces/filestreamfactory) | Define los métodos requeridos para instanciar y liberar un flujo de archivo de salida. |
| [PageStreamFactory](../com.groupdocs.viewer.interfaces/pagestreamfactory) | Define los métodos requeridos para instanciar y liberar un flujo de página de salida. |
| [ReleaseFileStream](../com.groupdocs.viewer.interfaces/releasefilestream) | Libera una interfaz que fue instanciada por el método asociado con la interfaz CreateFileStream. |
| [ReleasePageStream](../com.groupdocs.viewer.interfaces/releasepagestream) | Libera un flujo que fue instanciado por el método asociado con la interfaz CreatePageStream. |
| [ReleaseResourceStream](../com.groupdocs.viewer.interfaces/releaseresourcestream) | Libera un flujo que fue instanciado por el método asociado con la interfaz CreateResourceStream. |
| [ResourceStreamFactory](../com.groupdocs.viewer.interfaces/resourcestreamfactory) | Define los métodos requeridos para crear una URL de recurso, instanciar y liberar un flujo de recurso HTML de salida. |
