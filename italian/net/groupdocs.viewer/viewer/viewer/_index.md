---
title: "Viewer"
second_title: "GroupDocs.Viewer per .NET API Reference"
description: "Inizializza una nuova istanza della classe Viewergroupdocs.viewer/viewer."
type: docs
weight: 10
url: /it/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *getFileStream* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| getLoadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *getFileStream* è nullo. |
| ArgumentNullException | Generato quando *getLoadOptions* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *getFileStream* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| getFileStream | Func`1 | Il metodo che restituisce un flusso leggibile. |
| getLoadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *getFileStream* è nullo. |
| ArgumentNullException | Generato quando *getLoadOptions* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| leaveOpen | Boolean | true per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, false. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| leaveOpen | Boolean | true per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, false. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| settings | ViewerSettings | Le impostazioni del Viewer. |
| leaveOpen | Boolean | true per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, false. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| stream | Stream | Lo stream del file. |
| loadOptions | LoadOptions | Le opzioni di caricamento del documento. |
| settings | ViewerSettings | Le impostazioni del Viewer. |
| leaveOpen | Boolean | true per lasciare il flusso aperto dopo che l'oggetto Viewer è stato eliminato; altrimenti, false. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *stream* è nullo. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| percorsoFile | Stringa | Il percorso del file da renderizzare. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePath* è nullo o vuoto. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| percorsoFile | Stringa | Il percorso del file da renderizzare. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePath* è nullo o vuoto. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Vedi anche

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| percorsoFile | Stringa | Il percorso del file da renderizzare. |
| loadOptions | LoadOptions | Le opzioni che venivano usate per aprire il file. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePath* è nullo o vuoto. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Inizializza una nuova istanza della classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parametro | Type | Descrizione |
| --- | --- | --- |
| percorsoFile | Stringa | Il percorso del file da renderizzare. |
| loadOptions | LoadOptions | Le opzioni che venivano usate per aprire il file. |
| settings | ViewerSettings | Le impostazioni del Viewer. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generato quando *filePath* è nullo o vuoto. |
| ArgumentNullException | Generato quando *loadOptions* è nullo. |
| ArgumentNullException | Generato quando *settings* è nullo. |

### Osservazioni

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Vedi anche

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
