---
title: "ForExternalResources"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions para renderizar en HTML con recursos externos."
type: docs
weight: 20
url: /es/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| createResourceStream | CreateResourceStream | El método que libera el flujo creado por el método *createPageStream*. |
| createResourceUrl | CreateResourceUrl | El método que crea la URL para el recurso HTML. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |
| ArgumentNullException | Se lanza cuando *createResourceStream* es nulo. |
| ArgumentNullException | Se lanza cuando *createResourceUrl* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| createResourceStream | CreateResourceStream | El método que instancia el flujo utilizado para escribir los datos del recurso HTML de salida. |
| createResourceUrl | CreateResourceUrl | El método que crea la URL para el recurso HTML. |
| releasePageStream | ReleasePageStream | El método que libera el flujo creado por el método asignado al delegado que se pasó al parámetro *createPageStream*. |
| releaseResourceStream | ReleaseResourceStream | El método que libera el flujo creado por el método asignado al delegado que se pasó al parámetro *createResourceStream*. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |
| ArgumentNullException | Se lanza cuando *createResourceStream* es nulo. |
| ArgumentNullException | Se lanza cuando *createResourceUrl* es nulo. |
| ArgumentNullException | Se lanza cuando *releasePageStream* es nulo. |
| ArgumentNullException | Se lanza cuando *releaseResourceStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |
| resourceStreamFactory | IResourceStreamFactory | La fábrica que implementa los métodos necesarios para crear la URL del recurso, instanciar y liberar el flujo del recurso HTML de salida. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *pageStreamFactory* es nulo. |
| ArgumentNullException | Se lanza cuando *resourceStreamFactory* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Ver también

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Observaciones

Este constructor inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions)

* with "p_{0}.html" as file path format for the output HTML files
* with "p_{0}_{1}" as file path format for the output HTML-resource files
* with "p_{0}_{1}" as URL format for HTML-resources

Los archivos de salida se colocarán en el directorio de trabajo actual de la aplicación.

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de ruta de archivo, por ejemplo 'page_{0}.html'. |
| resourceFilePathFormat | String | El formato de ruta del archivo de recurso, p. ej. 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | El formato de URL del recurso, p. ej. 'page_{0}/resource_{1}'. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *filePathFormat* es nulo o está vacío. |
| ArgumentException | Se lanza cuando *resourceFilePathFormat* es nulo o está vacío. |
| ArgumentException | Se lanza cuando *resourceUrlFormat* es nulo o está vacío. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-external-resources).

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
