---
title: Viewer
second_title: GroupDocs.Viewer for .NET API Reference
description: Initializes new instance of Viewergroupdocs.viewer/viewer class.
type: docs
weight: 10
url: /net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| getLoadOptions | Func`1 | The methods that returns document load options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *getLoadOptions* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | The method that returns readable stream. |
| getLoadOptions | Func`1 | The methods that returns document load options. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *getFileStream* is null. |
| ArgumentNullException | Thrown when *getLoadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| leaveOpen | Boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| loadOptions | LoadOptions | The document load options. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| loadOptions | LoadOptions | The document load options. |
| leaveOpen | Boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| settings | ViewerSettings | The Viewer settings. |
| leaveOpen | Boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| loadOptions | LoadOptions | The document load options. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The file stream. |
| loadOptions | LoadOptions | The document load options. |
| settings | ViewerSettings | The Viewer settings. |
| leaveOpen | Boolean | true to leave the stream open after the Viewer object is disposed; otherwise, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *stream* is null. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePath* is null or empty. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### See Also

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| loadOptions | LoadOptions | The options that used to open the file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *loadOptions* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initializes new instance of [`Viewer`](../../viewer) class.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to render. |
| loadOptions | LoadOptions | The options that used to open the file. |
| settings | ViewerSettings | The Viewer settings. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Thrown when *filePath* is null or empty. |
| ArgumentNullException | Thrown when *loadOptions* is null. |
| ArgumentNullException | Thrown when *settings* is null. |

### Remarks

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### See Also

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
