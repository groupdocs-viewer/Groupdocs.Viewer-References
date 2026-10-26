---
title: "Viewer"
second_title: "GroupDocs.Viewer for .NET API-referentie"
description: "Initialiseert een nieuwe instantie van de Viewergroupdocs.viewer/viewer klasse."
type: docs
weight: 10
url: /nl/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *getFileStream* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| getLoadOptions | Func`1 | De methoden die documentlaadopties retourneren. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *getFileStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *getLoadOptions* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *getFileStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| getFileStream | Func`1 | De methode die een leesbare stream retourneert. |
| getLoadOptions | Func`1 | De methoden die documentlaadopties retourneren. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *getFileStream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *getLoadOptions* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| leaveOpen | Boolean | true om de stream open te laten na het vrijgeven van het Viewer-object; anders false. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| loadOptions | LoadOptions | De documentlaadopties. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| loadOptions | LoadOptions | De documentlaadopties. |
| leaveOpen | Boolean | true om de stream open te laten na het vrijgeven van het Viewer-object; anders false. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| settings | ViewerSettings | De Viewer-instellingen. |
| leaveOpen | Boolean | true om de stream open te laten na het vrijgeven van het Viewer-object; anders false. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| loadOptions | LoadOptions | De documentlaadopties. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | Stream | De bestands‑stream. |
| loadOptions | LoadOptions | De documentlaadopties. |
| settings | ViewerSettings | De Viewer-instellingen. |
| leaveOpen | Boolean | true om de stream open te laten na het vrijgeven van het Viewer-object; anders false. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *stream* null is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand om te renderen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *filePath* null of leeg is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand om te renderen. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *filePath* null of leeg is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Zie ook

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand om te renderen. |
| loadOptions | LoadOptions | De opties die werden gebruikt om het bestand te openen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *filePath* null of leeg is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialiseert een nieuwe instantie van de [`Viewer`](../../viewer) klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het pad naar het bestand om te renderen. |
| loadOptions | LoadOptions | De opties die werden gebruikt om het bestand te openen. |
| settings | ViewerSettings | De Viewer-instellingen. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer *filePath* null of leeg is. |
| ArgumentNullException | Wordt gegooid wanneer *loadOptions* null is. |
| ArgumentNullException | Wordt gegooid wanneer *settings* null is. |

### Opmerkingen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Zie ook

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
