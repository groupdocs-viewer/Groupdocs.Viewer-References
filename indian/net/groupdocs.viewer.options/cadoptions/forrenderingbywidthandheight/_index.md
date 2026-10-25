---
title: "ForRenderingByWidthAndHeight"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "CadOptionsgroupdocs.viewer.options/cadoptions क्लास का एक इंस्टेंस इनिशियलाइज़ करता है, जो चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए है।"
type: docs
weight: 40
url: /hi/net/groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight/
---

## CadOptions.ForRenderingByWidthAndHeight method

[`CadOptions`](../../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है, जो चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए है।

```csharp
public static CadOptions ForRenderingByWidthAndHeight(int width, int height)
```

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | Int32 | आउटपुट परिणाम की चौड़ाई (पिक्सेल में)। |
| height | Int32 | आउटपुट परिणाम की ऊँचाई (पिक्सेल में)। |

### वापसी मान

[`CadOptions`](../../cadoptions) क्लास का नया इंस्टेंस, जो चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए है।

### एक्सेप्शन

| एक्सेप्शन | शर्त |
| --- | --- |
| ArgumentException | जब *width* शून्य या उससे कम हो तो थ्रो किया जाता है। |
| ArgumentException | जब *height* शून्य या उससे कम हो तो थ्रो किया जाता है। |

### टिप्पणियाँ

कोड उदाहरण के लिए, देखें [डॉक्यूमेंटेशन](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/#configure-the-output-image-size)।

### संबंधित देखें

* class [CadOptions](../../cadoptions)
* namespace [GroupDocs.Viewer.Options](../../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
