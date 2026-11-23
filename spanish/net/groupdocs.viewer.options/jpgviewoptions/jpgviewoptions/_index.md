---
title: "JpgViewOptions"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase JpgViewOptionsgroupdocs.viewer.options/jpgviewoptions."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.options/jpgviewoptions/jpgviewoptions/
---

## JpgViewOptions(CreatePageStream) {#constructor_1}

Inicializa una instancia de la clase [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia un flujo utilizado para escribir los datos de la página de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(CreatePageStream, ReleasePageStream) {#constructor_2}

Inicializa una instancia de la clase [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia un flujo utilizado para escribir los datos de la página de salida. |
| releasePageStream | ReleasePageStream | El método que libera un flujo creado por el método asignado al delegado que se pasó al parámetro *createPageStream*. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |
| ArgumentNullException | Se lanza cuando *releasePageStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(IPageStreamFactory) {#constructor_3}

Inicializa una instancia de la clase [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(IPageStreamFactory pageStreamFactory)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *pageStreamFactory* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Ver también

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions() {#constructor}

Inicializa una instancia de la clase [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions()
```

### Observaciones

Este constructor inicializa una instancia de la [`JpgViewOptions`](../../jpgviewoptions) con "p_{0}.jpg" como formato de ruta de archivo para los archivos de salida. Los archivos de salida se colocan en el directorio de trabajo actual de la aplicación.

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Ver también

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## JpgViewOptions(string) {#constructor_4}

Inicializa una instancia de la clase [`JpgViewOptions`](../../jpgviewoptions).

```csharp
public JpgViewOptions(string filePathFormat)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de ruta de archivo, por ejemplo 'page_{0}.jpg'. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *filePathFormat* es nulo o está vacío. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/#rendering-to-jpeg).

### Ver también

* class [JpgViewOptions](../../jpgviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
