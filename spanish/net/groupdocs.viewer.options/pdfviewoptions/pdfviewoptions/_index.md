---
title: "PdfViewOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase PdfViewOptionsgroupdocs.viewer.options/pdfviewoptions."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.options/pdfviewoptions/pdfviewoptions/
---

## PdfViewOptions(CreateFileStream) {#constructor_1}

Inicializa una instancia de la clase [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createFileStream | CreateFileStream | El método que instancia el flujo utilizado para escribir los datos del archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada cuando *createFileStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Ver también

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(CreateFileStream, ReleaseFileStream) {#constructor_2}

Inicializa una instancia de la clase [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(CreateFileStream createFileStream, ReleaseFileStream releaseFileStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createFileStream | CreateFileStream | El método que instancia el flujo utilizado para escribir los datos del archivo de salida. |
| releaseFileStream | ReleaseFileStream | El método que libera el flujo creado por el método asignado al delegado que se pasó al parámetro *createFileStream*. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzada cuando *createFileStream* es nulo. |
| ArgumentNullException | Lanzada cuando *releaseFileStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Ver también

* delegate [CreateFileStream](../../../groupdocs.viewer.interfaces/createfilestream)
* delegate [ReleaseFileStream](../../../groupdocs.viewer.interfaces/releasefilestream)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(IFileStreamFactory) {#constructor_3}

Inicializa una instancia de la clase [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(IFileStreamFactory fileStreamFactory)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| fileStreamFactory | IFileStreamFactory | La fábrica que implementa métodos para crear y liberar el flujo de archivo de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *fileStreamFactory* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Ver también

* interface [IFileStreamFactory](../../../groupdocs.viewer.interfaces/ifilestreamfactory)
* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions() {#constructor}

Inicializa una instancia de la clase [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions()
```

### Observaciones

Este constructor inicializa una instancia de [`PdfViewOptions`](../../pdfviewoptions) con "output.pdf" como formato de ruta de archivo para el archivo de salida. El archivo de salida se colocará en el directorio de trabajo actual de la aplicación.

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Ver también

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## PdfViewOptions(string) {#constructor_4}

Inicializa una instancia de la clase [`PdfViewOptions`](../../pdfviewoptions).

```csharp
public PdfViewOptions(string outputFilePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| outputFilePath | String | La ruta del archivo PDF de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *outputFilePath* es nulo o está vacío. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).

### Ver también

* class [PdfViewOptions](../../pdfviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
