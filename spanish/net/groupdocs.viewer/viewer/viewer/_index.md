---
title: "Viewer"
second_title: "Referencia de la API de GroupDocs.Viewer para .NET"
description: "Inicializa una nueva instancia de la clase Viewergroupdocs.viewer/viewer."
type: docs
weight: 10
url: /es/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *getFileStream* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| getLoadOptions | Func`1 | Los métodos que devuelven las opciones de carga del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *getFileStream* es nulo. |
| ArgumentNullException | Lanzado cuando *getLoadOptions* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *getFileStream* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| getLoadOptions | Func`1 | Los métodos que devuelven las opciones de carga del documento. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *getFileStream* es nulo. |
| ArgumentNullException | Lanzado cuando *getLoadOptions* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| leaveOpen | Boolean | true para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, false. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| loadOptions | LoadOptions | Las opciones de carga del documento. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| loadOptions | LoadOptions | Las opciones de carga del documento. |
| leaveOpen | Boolean | true para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, false. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| settings | ViewerSettings | La configuración del Viewer. |
| leaveOpen | Boolean | true para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, false. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| loadOptions | LoadOptions | Las opciones de carga del documento. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| flujo | Flujo | El flujo del archivo. |
| loadOptions | LoadOptions | Las opciones de carga del documento. |
| settings | ViewerSettings | La configuración del Viewer. |
| leaveOpen | Boolean | true para dejar el flujo abierto después de que el objeto Viewer sea eliminado; de lo contrario, false. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Lanzado cuando *stream* es nulo. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| loadOptions | LoadOptions | Las opciones que se usaban para abrir el archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Inicializa una nueva instancia de la clase [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parámetro | Type | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| loadOptions | LoadOptions | Las opciones que se usaban para abrir el archivo. |
| settings | ViewerSettings | La configuración del Viewer. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Lanzado cuando *filePath* es nulo o está vacío. |
| ArgumentNullException | Lanzado cuando *loadOptions* es nulo. |
| ArgumentNullException | Lanzado cuando *settings* es nulo. |

### Observaciones

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Viewer.dll -->
