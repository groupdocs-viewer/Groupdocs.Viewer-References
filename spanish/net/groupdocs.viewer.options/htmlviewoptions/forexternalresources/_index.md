---
title: ForExternalResources
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Inicializa una nueva instancia deHtmlViewOptionsgroupdocs.viewer.options/htmlviewoptions clase para renderizar en HTML con recursos externos.
type: docs
weight: 20
url: /es/net/groupdocs.viewer.options/htmlviewoptions/forexternalresources/
---
## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl) {#forexternalresources_1}

Inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| createResourceStream | CreateResourceStream | El método que libera flujo creado por*createPageStream* método. |
| createResourceUrl | CreateResourceUrl | El método que crea la URL para el recurso HTML. |

### Valor_devuelto

Nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*createPageStream* es nulo. |
| ArgumentNullException | arrojado cuando*createResourceStream* es nulo. |
| ArgumentNullException | arrojado cuando*createResourceUrl* es nulo. |

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* class [HtmlViewOptions](../../htmlviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../htmlviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) {#forexternalresources_2}

Inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(CreatePageStream createPageStream, 
    CreateResourceStream createResourceStream, CreateResourceUrl createResourceUrl, 
    ReleasePageStream releasePageStream, ReleaseResourceStream releaseResourceStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| createPageStream | CreatePageStream | El método que instancia el flujo utilizado para escribir los datos de la página de salida. |
| createResourceStream | CreateResourceStream | El método que instancia el flujo utilizado para escribir datos de recursos HTML de salida. |
| createResourceUrl | CreateResourceUrl | El método que crea la URL para el recurso HTML. |
| releasePageStream | ReleasePageStream | El método que libera el flujo creado por el método asignado al delegado que pasó a*createPageStream* parámetro. |
| releaseResourceStream | ReleaseResourceStream | El método que libera el flujo creado por el método asignado al delegado que pasó a*createResourceStream* parámetro. |

### Valor_devuelto

Nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*createPageStream* es nulo. |
| ArgumentNullException | arrojado cuando*createResourceStream* es nulo. |
| ArgumentNullException | arrojado cuando*createResourceUrl* es nulo. |
| ArgumentNullException | arrojado cuando*releasePageStream* es nulo. |
| ArgumentNullException | arrojado cuando*releaseResourceStream* es nulo. |

### Ver también

* delegate [CreatePageStream](../../../groupdocs.viewer.interfaces/createpagestream)
* delegate [CreateResourceStream](../../../groupdocs.viewer.interfaces/createresourcestream)
* delegate [CreateResourceUrl](../../../groupdocs.viewer.interfaces/createresourceurl)
* delegate [ReleasePageStream](../../../groupdocs.viewer.interfaces/releasepagestream)
* delegate [ReleaseResourceStream](../../../groupdocs.viewer.interfaces/releaseresourcestream)
* class [HtmlViewOptions](../../htmlviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../htmlviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(IPageStreamFactory, IResourceStreamFactory) {#forexternalresources_3}

Inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

```csharp
public static HtmlViewOptions ForExternalResources(IPageStreamFactory pageStreamFactory, 
    IResourceStreamFactory resourceStreamFactory)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| pageStreamFactory | IPageStreamFactory | La fábrica que implementa métodos para crear y publicar secuencias de páginas de salida. |
| resourceStreamFactory | IResourceStreamFactory | La fábrica que implementa los métodos que se requieren para crear la URL del recurso, instanciar y liberar el flujo de recursos HTML de salida. |

### Valor_devuelto

Nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase para renderizar en HTML con recursos externos.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*pageStreamFactory* es nulo. |
| ArgumentNullException | arrojado cuando*resourceStreamFactory* es nulo. |

### Ver también

* interface [IPageStreamFactory](../../../groupdocs.viewer.interfaces/ipagestreamfactory)
* interface [IResourceStreamFactory](../../../groupdocs.viewer.interfaces/iresourcestreamfactory)
* class [HtmlViewOptions](../../htmlviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../htmlviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources() {#forexternalresources}

Inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase.

```csharp
public static HtmlViewOptions ForExternalResources()
```

### Observaciones

Este constructor inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) - con "p_{0}.html" como formato de ruta de archivo para los archivos HTML de salida; - con "p_{0}_{1}" como formato de ruta de archivo para los archivos de recursos HTML de salida; - con " p_{0}_{1}" como formato URL para recursos HTML; Los archivos de salida se colocarán en el directorio de trabajo actual de la aplicación.

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../htmlviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

---

## ForExternalResources(string, string, string) {#forexternalresources_4}

Inicializa una nueva instancia de[`HtmlViewOptions`](../../htmlviewoptions) clase.

```csharp
public static HtmlViewOptions ForExternalResources(string filePathFormat, 
    string resourceFilePathFormat, string resourceUrlFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePathFormat | String | El formato de la ruta del archivo, por ejemplo, 'page_{0}.html'. |
| resourceFilePathFormat | String | El formato de la ruta del archivo de recursos, por ejemplo, 'page_{0}/resource_{1}'. |
| resourceUrlFormat | String | El formato de la URL del recurso, por ejemplo, 'página_{0}/recurso_{1}'. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*filePathFormat* es nulo o vacío. |
| ArgumentException | arrojado cuando*resourceFilePathFormat* es nulo o vacío. |
| ArgumentException | arrojado cuando*resourceUrlFormat* es nulo o vacío. |

### Ver también

* class [HtmlViewOptions](../../htmlviewoptions)
* espacio de nombres [GroupDocs.Viewer.Options](../../htmlviewoptions)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
