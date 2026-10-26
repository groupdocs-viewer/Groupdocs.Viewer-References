---
title: "Viewer"
second_title: "GroupDocs.Viewer för .NET API-referens"
description: "Initierar en ny instans av Viewergroupdocs.viewer/viewer-klassen."
type: docs
weight: 10
url: /sv/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar en läsbar ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *getFileStream* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar en läsbar ström. |
| getLoadOptions | Func`1 | Metoderna som returnerar dokumentets laddningsalternativ. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *getFileStream* är null. |
| ArgumentNullException | Kastas när *getLoadOptions* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar en läsbar ström. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *getFileStream* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| getFileStream | Func`1 | Metoden som returnerar en läsbar ström. |
| getLoadOptions | Func`1 | Metoderna som returnerar dokumentets laddningsalternativ. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *getFileStream* är null. |
| ArgumentNullException | Kastas när *getLoadOptions* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| leaveOpen | Boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| loadOptions | LoadOptions | Dokumentets laddningsalternativ. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *loadOptions* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| loadOptions | LoadOptions | Dokumentets laddningsalternativ. |
| leaveOpen | Boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *loadOptions* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| settings | ViewerSettings | Viewer-inställningarna. |
| leaveOpen | Boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| loadOptions | LoadOptions | Dokumentets laddningsalternativ. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *loadOptions* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Ström | Filströmmen. |
| loadOptions | LoadOptions | Dokumentets laddningsalternativ. |
| settings | ViewerSettings | Viewer-inställningarna. |
| leaveOpen | Boolean | true för att lämna strömmen öppen efter att Viewer-objektet har frigjorts; annars false. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *stream* är null. |
| ArgumentNullException | Kastas när *loadOptions* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePath* är null eller tom. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePath* är null eller tom. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Se även

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| loadOptions | LoadOptions | Alternativen som används för att öppna filen. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePath* är null eller tom. |
| ArgumentNullException | Kastas när *loadOptions* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initierar en ny instans av [`Viewer`](../../viewer)-klassen.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Sökvägen till filen som ska renderas. |
| loadOptions | LoadOptions | Alternativen som används för att öppna filen. |
| settings | ViewerSettings | Viewer-inställningarna. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentException | Kastas när *filePath* är null eller tom. |
| ArgumentNullException | Kastas när *loadOptions* är null. |
| ArgumentNullException | Kastas när *settings* är null. |

### Anmärkningar

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Se även

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
