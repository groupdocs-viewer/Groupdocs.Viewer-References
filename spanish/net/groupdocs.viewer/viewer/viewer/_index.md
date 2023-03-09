---
title: Viewer
second_title: Referencia de API de GroupDocs.Viewer para .NET
description: Inicializa una nueva instancia deViewergroupdocs.viewer/viewer clase.
type: docs
weight: 10
url: /es/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| getLoadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*getLoadOptions* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| getFileStream | Func`1 | El método que devuelve un flujo legible. |
| getLoadOptions | Func`1 | Los métodos que devuelven las opciones de carga de documentos. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*getFileStream* es nulo. |
| ArgumentNullException | arrojado cuando*getLoadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| leaveOpen | Boolean | verdadero para dejar la secuencia abierta después de desechar el objeto Visor; de lo contrario,FALSO. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| loadOptions | LoadOptions | Las opciones de carga de documentos. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| loadOptions | LoadOptions | Las opciones de carga de documentos. |
| leaveOpen | Boolean | verdadero para dejar la secuencia abierta después de desechar el objeto Visor; de lo contrario,FALSO. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| settings | ViewerSettings | La configuración del visor. |
| leaveOpen | Boolean | verdadero para dejar la secuencia abierta después de desechar el objeto Visor; de lo contrario,FALSO. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| loadOptions | LoadOptions | Las opciones de carga de documentos. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de archivos. |
| loadOptions | LoadOptions | Las opciones de carga de documentos. |
| settings | ViewerSettings | La configuración del visor. |
| leaveOpen | Boolean | verdadero para dejar la secuencia abierta después de desechar el objeto Visor; de lo contrario,FALSO. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | arrojado cuando*stream* es nulo. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*filePath* es nulo o vacío. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Ver también

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| loadOptions | LoadOptions | Las opciones que se utilizan para abrir el archivo. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Inicializa una nueva instancia de[`Viewer`](../../viewer) clase.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | La ruta al archivo a renderizar. |
| loadOptions | LoadOptions | Las opciones que se utilizan para abrir el archivo. |
| settings | ViewerSettings | La configuración del visor. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | arrojado cuando*filePath* es nulo o vacío. |
| ArgumentNullException | arrojado cuando*loadOptions* es nulo. |
| ArgumentNullException | arrojado cuando*settings* es nulo. |

### Observaciones

**Aprende más**

* Más información sobre los tipos de archivos admitidos por GroupDocs.Viewer: [Formatos de documentos compatibles con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* Más acerca de las características de GroupDocs.Viewer para .NET: [Guía del desarrollador](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* Más información sobre la carga de documentos cifrados y la visualización de archivos desde almacenamientos de terceros con GroupDocs.Viewer para .NET: [Cómo cargar y ver documentos con GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Ver también

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* espacio de nombres [GroupDocs.Viewer](../../viewer)
* asamblea [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
