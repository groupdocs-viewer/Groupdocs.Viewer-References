---
title: "व्यूअर"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Viewergroupdocs.viewer/viewer क्लास का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer/viewer/viewer/
---

## Viewer(Func&lt;Stream&gt;) {#constructor}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Func<Stream> getFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाला मेथड। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाला मेथड। |
| getLoadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाले मेथड्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *getLoadOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाला मेथड। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | पढ़ने योग्य स्ट्रीम लौटाने वाला मेथड। |
| getLoadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाले मेथड्स। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *getFileStream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *getLoadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| leaveOpen | Boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| leaveOpen | Boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| settings | ViewerSettings | Viewer सेटिंग्स। |
| leaveOpen | Boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | ViewerSettings | Viewer सेटिंग्स। |
| leaveOpen | Boolean | Viewer ऑब्जेक्ट डिस्पोज़ होने के बाद स्ट्रीम को खुला रखने के लिए true; अन्यथा false। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *stream* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | रेंडर करने के लिए फ़ाइल का पथ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | रेंडर करने के लिए फ़ाइल का पथ। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### संबंधित देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | रेंडर करने के लिए फ़ाइल का पथ। |
| loadOptions | LoadOptions | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

[`Viewer`](../../viewer) क्लास का नया उदाहरण प्रारंभ करता है।

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | रेंडर करने के लिए फ़ाइल का पथ। |
| loadOptions | LoadOptions | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |
| settings | ViewerSettings | Viewer सेटिंग्स। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *filePath* null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | जब *loadOptions* null हो तो फेंका जाता है। |
| ArgumentNullException | जब *settings* null हो तो फेंका जाता है। |

### टिप्पणियाँ

**Learn more**

* More about file types supported by GroupDocs.Viewer: [Document formats supported by GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* More about GroupDocs.Viewer for .NET features: [Developer Guide](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* More about loading encrypted documents and viewing files from third-party storages with GroupDocs.Viewer for .NET: [How to load and view document with GroupDocs.Viewer](https://docs.groupdocs.com/display/viewernet/Loading)

### संबंधित देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* namespace [GroupDocs.Viewer](../../../groupdocs.viewer)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
