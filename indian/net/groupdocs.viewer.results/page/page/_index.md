---
title: "Page"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Pagegroupdocs.viewer.results/page क्लास का नया उदाहरण आरंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/page/page/
---

## Page() {#constructor}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page()
```

### संबंधित देखें

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool) {#constructor_1}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, bool visible)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |

### संबंधित देखें

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool) {#constructor_4}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, string name, bool visible)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| नाम | String | वर्कशीट या पृष्ठ का नाम। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |

### संबंधित देखें

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int) {#constructor_2}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, bool visible, int width, int height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |
| width | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में। |
| height | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |

### संबंधित देखें

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int) {#constructor_5}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, string name, bool visible, int width, int height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| नाम | String | वर्कशीट या पृष्ठ का नाम। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |
| width | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में। |
| height | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |

### संबंधित देखें

* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, bool, int, int, List&lt;Line&gt;) {#constructor_3}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, bool visible, int width, int height, List<Line> lines)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |
| width | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में। |
| height | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में। |
| पंक्तियाँ | List`1 | JPG या PNG के रूप में, टेक्स्ट निष्कर्षण सक्षम होने पर पृष्ठ में सम्मिलित पंक्तियाँ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentNullException | जब *lines* शून्य (null) हो तो फेंका जाता है। |

### संबंधित देखें

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Page(int, string, bool, int, int, List&lt;Line&gt;) {#constructor_6}

[`Page`](../../page) क्लास का नया उदाहरण आरंभ करता है।

```csharp
public Page(int number, string name, bool visible, int width, int height, List<Line> lines)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| संख्या | Int32 | पृष्ठ संख्या। |
| नाम | String | वर्कशीट या पृष्ठ का नाम। |
| दृश्यमान | Boolean | पृष्ठ दृश्यता संकेतक। |
| width | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की चौड़ाई पिक्सेल में। |
| height | Int32 | JPG या PNG के रूप में देखते समय पृष्ठ की ऊँचाई पिक्सेल में। |
| पंक्तियाँ | List`1 | JPG या PNG के रूप में, टेक्स्ट निष्कर्षण सक्षम होने पर पृष्ठ में सम्मिलित पंक्तियाँ। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *number* शून्य या उससे कम हो तो फेंका जाता है। |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentNullException | जब *lines* शून्य (null) हो तो फेंका जाता है। |

### संबंधित देखें

* class [Line](../../line)
* class [Page](../../page)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
