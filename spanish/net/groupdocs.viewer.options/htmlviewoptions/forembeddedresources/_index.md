---
title: "ForEmbeddedResources"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una instancia de la clase HtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions para renderizar en HTML con recursos incrustados."
type: docs
weight: 10
url: /es/net/groupdocs.viewer.options/htmlviewoptions/forembeddedresources/
---

## ForEmbeddedResources(CreatePageStream) {#forembeddedresources_1}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(CreatePageStream, ReleasePageStream) {#forembeddedresources_2}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

```csharp
public static HtmlViewOptions ForEmbeddedResources(CreatePageStream createPageStream, 
    ReleasePageStream releasePageStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| releasePageStream | ReleasePageStream | El método que libera el flujo creado por el método asignado al delegado que se pasó al parámetro *createPageStream*. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *createPageStream* es nulo. |
| ArgumentNullException | Se lanza cuando *releasePageStream* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(IPageStreamFactory) {#forembeddedresources_3}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

```csharp
public static HtmlViewOptions ForEmbeddedResources(IPageStreamFactory pageStreamFactory)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fábrica que implementa métodos para crear y liberar el flujo de página de salida. |

### Valor devuelto

Nueva instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions) para renderizar en HTML con recursos incrustados.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza cuando *pageStreamFactory* es nulo. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Ver también

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources() {#forembeddedresources}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources()
```

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

---

## ForEmbeddedResources(string) {#forembeddedresources_4}

Inicializa una instancia de la clase [`HtmlViewOptions`](../../htmlviewoptions).

```csharp
public static HtmlViewOptions ForEmbeddedResources(string filePathFormat)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de ruta de archivo, por ejemplo 'page_{0}.html'. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando *filePathFormat* es nulo o está vacío. |

### Observaciones

Para el ejemplo de código, consulte la [documentación](https://docs.groupdocs.com/viewer/net/rendering-to-html/#rendering-to-html-with-embedded-resources).

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
