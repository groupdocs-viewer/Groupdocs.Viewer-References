---
title: "Visionneuse"
second_title: "Référence d'API GroupDocs.Viewer pour .NET"
description: "Initialise une nouvelle instance de la classe Viewergroupdocs.viewer/viewer."
type: docs
weight: 10
url: /fr/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| getLoadOptions | Func`1 | Les méthodes qui renvoient les options de chargement du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *getLoadOptions* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| getFileStream | Func`1 | La méthode qui renvoie un flux lisible. |
| getLoadOptions | Func`1 | Les méthodes qui renvoient les options de chargement du document. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *getFileStream* est nul. |
| ArgumentNullException | Lancée lorsque *getLoadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| leaveOpen | Boolean | true pour laisser le flux ouvert après la libération de l'objet Viewer; sinon, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| loadOptions | LoadOptions | Les options de chargement du document. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| loadOptions | LoadOptions | Les options de chargement du document. |
| leaveOpen | Boolean | true pour laisser le flux ouvert après la libération de l'objet Viewer; sinon, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| settings | ViewerSettings | Les paramètres du Viewer. |
| leaveOpen | Boolean | true pour laisser le flux ouvert après la libération de l'objet Viewer; sinon, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| loadOptions | LoadOptions | Les options de chargement du document. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux de fichier. |
| loadOptions | LoadOptions | Les options de chargement du document. |
| settings | ViewerSettings | Les paramètres du Viewer. |
| leaveOpen | Boolean | true pour laisser le flux ouvert après la libération de l'objet Viewer; sinon, false. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *stream* est nul. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à rendre. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à rendre. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### Voir aussi

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à rendre. |
| loadOptions | LoadOptions | Les options qui étaient utilisées pour ouvrir le fichier. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

Initialise une nouvelle instance de la classe [`Viewer`](../../viewer).

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier à rendre. |
| loadOptions | LoadOptions | Les options qui étaient utilisées pour ouvrir le fichier. |
| settings | ViewerSettings | Les paramètres du Viewer. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Lancée lorsque *filePath* est nul ou vide. |
| ArgumentNullException | Lancée lorsque *loadOptions* est nul. |
| ArgumentNullException | Lancée lorsque *settings* est nul. |

### Remarques

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### Voir aussi

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Viewer.dll -->
