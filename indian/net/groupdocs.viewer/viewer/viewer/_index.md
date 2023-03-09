---
title: Viewer
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: क नय उदहरण शुरू करत हैViewergroupdocs.viewer/viewer वर्ग.
type: docs
weight: 10
url: /hi/net/groupdocs.viewer/viewer/viewer/
---
## Viewer(Func&lt;Stream&gt;) {#constructor}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Func<Stream> getFileStream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_2}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| getLoadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*getLoadOptions* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, ViewerSettings) {#constructor_1}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Func<Stream> getFileStream, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, ViewerSettings) {#constructor_3}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Func<Stream> getFileStream, Func<LoadOptions> getLoadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| getFileStream | Func`1 | वह विधि जो पठनीय स्ट्रीम लौटाती है। |
| getLoadOptions | Func`1 | दस्तावेज़ लोड विकल्प लौटाने वाली विधियाँ। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*getFileStream* शून्य है। |
| ArgumentNullException | कब फेंका*getLoadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream) {#constructor_4}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, bool) {#constructor_5}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| leaveOpen | Boolean | सत्य व्यूअर ऑब्जेक्ट के निपटारे के बाद स्ट्रीम को खुला छोड़ दें; अन्यथा,असत्य. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions) {#constructor_6}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, bool) {#constructor_7}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| leaveOpen | Boolean | सत्य व्यूअर ऑब्जेक्ट के निपटारे के बाद स्ट्रीम को खुला छोड़ दें; अन्यथा,असत्य. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings) {#constructor_10}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, ViewerSettings, bool) {#constructor_11}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, ViewerSettings settings, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |
| leaveOpen | Boolean | सत्य व्यूअर ऑब्जेक्ट के निपटारे के बाद स्ट्रीम को खुला छोड़ दें; अन्यथा,असत्य. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings) {#constructor_8}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(Stream, LoadOptions, ViewerSettings, bool) {#constructor_9}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(Stream stream, LoadOptions loadOptions, ViewerSettings settings, bool leaveOpen)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | Stream | फ़ाइल स्ट्रीम। |
| loadOptions | LoadOptions | दस्तावेज़ लोड विकल्प। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |
| leaveOpen | Boolean | सत्य व्यूअर ऑब्जेक्ट के निपटारे के बाद स्ट्रीम को खुला छोड़ दें; अन्यथा,असत्य. |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentNullException | कब फेंका*stream* शून्य है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(string) {#constructor_12}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(string filePath)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | प्रस्तुत करने के लिए फ़ाइल का पथ। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | कब फेंका*filePath* शून्य या खाली है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(string, ViewerSettings) {#constructor_15}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(string filePath, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | प्रस्तुत करने के लिए फ़ाइल का पथ। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)

### यह सभी देखें

* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions) {#constructor_13}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(string filePath, LoadOptions loadOptions)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | प्रस्तुत करने के लिए फ़ाइल का पथ। |
| loadOptions | LoadOptions | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

---

## Viewer(string, LoadOptions, ViewerSettings) {#constructor_14}

का नया उदाहरण शुरू करता है[`Viewer`](../../viewer) वर्ग.

```csharp
public Viewer(string filePath, LoadOptions loadOptions, ViewerSettings settings)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePath | String | प्रस्तुत करने के लिए फ़ाइल का पथ। |
| loadOptions | LoadOptions | फ़ाइल खोलने के लिए उपयोग किए जाने वाले विकल्प। |
| settings | ViewerSettings | दर्शक सेटिंग्स। |

### अपवाद

| अपवाद | स्थिति |
| --- | --- |
| ArgumentException | कब फेंका*filePath* शून्य या खाली है। |
| ArgumentNullException | कब फेंका*loadOptions* शून्य है। |
| ArgumentNullException | कब फेंका*settings* शून्य है। |

### टिप्पणियों

**और अधिक जानें**

* GroupDocs द्वारा समर्थित फ़ाइल प्रकारों के बारे में अधिक। व्यूअर: [GroupDocs.Viewer द्वारा समर्थित दस्तावेज़ स्वरूप](https://docs.groupdocs.com/display/viewernet/Supported+Document+Formats)
* .NET सुविधाओं के लिए GroupDocs.Viewer के बारे में अधिक जानकारी: [डेवलपर गाइड](https://docs.groupdocs.com/display/viewernet/Developer+Guide)
* एन्क्रिप्टेड दस्तावेज़ों को लोड करने और GroupDocs के साथ तृतीय-पक्ष संग्रहण से फ़ाइलें देखने के बारे में अधिक जानकारी। .NET: के लिए व्यूअर[GroupDocs.Viewer के साथ दस्तावेज़ को कैसे लोड करें और देखें](https://docs.groupdocs.com/display/viewernet/Loading)

### यह सभी देखें

* class [LoadOptions](../../../groupdocs.viewer.options/loadoptions)
* class [ViewerSettings](../../viewersettings)
* class [Viewer](../../viewer)
* नाम स्थान [GroupDocs.Viewer](../../viewer)
* सभा [GroupDocs.Viewer](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
