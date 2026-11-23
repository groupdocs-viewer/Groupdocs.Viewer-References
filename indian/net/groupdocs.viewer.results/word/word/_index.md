---
title: "शब्द"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "Wordgroupdocs.viewer.results/word क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 10
url: /hi/net/groupdocs.viewer.results/word/word/
---

## Word() {#constructor}

[`Word`](../../word) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Word()
```

### संबंधित देखें

* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

---

## Word(string, double, double, double, double, List&lt;Character&gt;) {#constructor_1}

[`Word`](../../word) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Word(string word, double x, double y, double width, double height, 
    List<Character> characters)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शब्द | String | शब्द। |
| x | Double | पेज लेआउट पर सबसे बाएँ ऊपरी बिंदु का X निर्देशांक जहाँ शब्द को सम्मिलित करने वाला आयत शुरू होता है। |
| y | Double | पेज लेआउट पर सबसे बाएँ ऊपरी बिंदु का Y निर्देशांक जहाँ शब्द को सम्मिलित करने वाला आयत शुरू होता है। |
| width | Double | शब्द को सम्मिलित करने वाले आयत की चौड़ाई। |
| height | Double | शब्द को सम्मिलित करने वाले आयत की ऊँचाई। |
| अक्षर | List`1 | शब्द में शामिल अक्षर। |

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *word* शून्य या खाली हो तो थ्रो किया जाता है। |
| ArgumentNullException | जब *characters* शून्य हो तो थ्रो किया जाता है। |

### संबंधित देखें

* class [Character](../../character)
* class [Word](../../word)
* namespace [GroupDocs.Viewer.Results](../../../groupdocs.viewer.results)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
