---
title: "Viewer"
second_title: "GroupDocs.Viewer für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Viewergroupdocs.viewer/viewer-Klasse."
type: docs
weight: 10
url: /de/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| getLoadOptions | Func`1 | Die Methoden, die Dokument-Ladeoptionen zurückgeben. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *getLoadOptions* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| getFileStream | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| getLoadOptions | Func`1 | Die Methoden, die Dokument-Ladeoptionen zurückgeben. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *getFileStream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *getLoadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| leaveOpen | Boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls false. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Dokument-Ladeoptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Dokument-Ladeoptionen. |
| leaveOpen | Boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls false. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |
| leaveOpen | Boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls false. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Dokument-Ladeoptionen. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| Stream | Stream | Der Dateistream. |
| loadOptions | LoadOptions | Die Dokument-Ladeoptionen. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |
| leaveOpen | Boolean | true, um den Stream nach der Entsorgung des Viewer-Objekts offen zu lassen; andernfalls false. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *stream* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(string filePath)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur zu rendernden Datei. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur zu rendernden Datei. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Siehe auch

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur zu rendernden Datei. |
| loadOptions | LoadOptions | Die Optionen, die zum Öffnen der Datei verwendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialisiert eine neue Instanz der [`Viewer`](../../viewer)-Klasse.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Pfad zur zu rendernden Datei. |
| loadOptions | LoadOptions | Die Optionen, die zum Öffnen der Datei verwendet werden. |
| settings | ViewerSettings | Die Viewer-Einstellungen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | Wird ausgelöst, wenn *filePath* null oder leer ist. |
| ArgumentNullException | Wird ausgelöst, wenn *loadOptions* null ist. |
| ArgumentNullException | Wird ausgelöst, wenn *settings* null ist. |

### Bemerkungen

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Siehe auch

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NICHT BEARBEITEN: von xmldocmd für GroupDocs.Viewer.dll generiert -->
