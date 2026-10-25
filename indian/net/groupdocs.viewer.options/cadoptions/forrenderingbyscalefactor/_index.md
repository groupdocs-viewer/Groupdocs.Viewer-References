---
title: "ForRenderingByScaleFactor"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए CadOptionsgroupdocs.viewer.options/cadoptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।"
type: docs
weight: 20
url: /hi/net/groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor/
---

## CadOptions.ForRenderingByScaleFactor method

स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए [`CadOptions`](../../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public static CadOptions ForRenderingByScaleFactor(float scaleFactor)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleFactor | Single | 1 से अधिक मान आउटपुट परिणाम को बड़ा करता है; 0 और 1 के बीच का मान आउटपुट परिणाम को घटाता है। |

### वापसी मान

स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए नया [`CadOptions`](../../cadoptions) क्लास इंस्टेंस।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | *scaleFactor* शून्य या उससे कम होने पर थ्रो किया जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size)।

### संबंधित देखें

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
