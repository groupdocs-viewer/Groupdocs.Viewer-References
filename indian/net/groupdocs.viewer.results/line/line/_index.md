---
title: "रेखा"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Linegroupdocs.viewer.results/line क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/line/line/
---

## Line() {#constructor}

[`Line`](../../line) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Line()
```

### संबंधित देखें

* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Line(string, double, double, double, double, List&lt;Word&gt;) {#constructor_1}

[`Line`](../../line) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Line(string line, double x, double y, double width, double height, List<Word> words)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| लाइन | String | यह लाइन। |
| x | Double | पृष्ठ लेआउट में सबसे बाएँ ऊपरी बिंदु का X निर्देशांक जहाँ वह आयत जो line को सम्मिलित करती है शुरू होती है। |
| y | Double | पृष्ठ लेआउट में सबसे बाएँ ऊपरी बिंदु का Y निर्देशांक जहाँ वह आयत जो line को सम्मिलित करती है शुरू होती है। |
| width | Double | लाइन को सम्मिलित करने वाली आयत की चौड़ाई (पिक्सेल में)। |
| height | Double | लाइन को सम्मिलित करने वाली आयत की ऊँचाई (पिक्सेल में)। |
| शब्द | List`1 | रेखा में शामिल शब्द। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *line* जब null या खाली हो तो फेंका जाता है। |
| ArgumentNullException | *words* जब null हो तो फेंका जाता है। |

### संबंधित देखें

* class [Word](../../word)
* class [Line](../../line)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
