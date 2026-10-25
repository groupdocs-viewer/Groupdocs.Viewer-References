---
title: "TextElement"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "TextElementgroupdocs.viewer.results/textelement1 वर्ग का नया उदाहरण प्रारंभ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/textelement-1/textelement/
---

## TextElement() {#constructor}

[`TextElement`](../../textelement-1) वर्ग का नया उदाहरण प्रारंभ करता है।

```csharp
public TextElement()
```

### संबंधित देखें

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## TextElement(T, double, double, double, double) {#constructor_1}

[`TextElement`](../../textelement-1) वर्ग का नया उदाहरण प्रारंभ करता है।

```csharp
public TextElement(T value, double x, double y, double width, double height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | T | पाठ तत्व का मान। |
| x | Double | पृष्ठ लेआउट पर सबसे बाएँ ऊँचे बिंदु का X निर्देशांक जहाँ तत्व को समाहित करने वाली आयत शुरू होती है। |
| y | Double | पृष्ठ लेआउट पर सबसे बाएँ ऊँचे बिंदु का Y निर्देशांक जहाँ तत्व को समाहित करने वाली आयत शुरू होती है। |
| width | Double | तत्व को समाहित करने वाले आयत की चौड़ाई (पिक्सेल में)। |
| height | Double | तत्व को समाहित करने वाले आयत की ऊँचाई (पिक्सेल में)। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentNullException | जब *value* null हो तो फेंका जाता है। |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |

### संबंधित देखें

* class [TextElement&lt;T&gt;](../../textelement-1)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
