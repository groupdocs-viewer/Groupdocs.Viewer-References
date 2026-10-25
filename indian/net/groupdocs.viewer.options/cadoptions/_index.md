---
title: "CadOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "CAD ड्रॉइंग्स को रेंडर करने के विकल्प शामिल हैं। अधिक जानकारी और कोड उदाहरणों के लिए देखें Render CAD drawings and models as HTML PDF and image files https//docs.groupdocs.com/viewer/net/rendercaddrawingsandmodels/ और Specify rendering options for CAD files https//docs.groupdocs.com/viewer/net/specifycadrenderingoptions/।"
type: docs
weight: 280
url: /hi/net/groupdocs.viewer.options/cadoptions/
---

## CadOptions class

CAD ड्रॉइंग्स को रेंडर करने के विकल्प शामिल हैं। अधिक जानकारी और कोड उदाहरणों के लिए, देखें [CAD ड्रॉइंग्स और मॉडल्स को HTML, PDF, और इमेज फ़ाइलों के रूप में रेंडर करें](https://docs.groupdocs.com/viewer/net/render-cad-drawings-and-models/) और [CAD फ़ाइलों के लिए रेंडरिंग विकल्प निर्दिष्ट करें](https://docs.groupdocs.com/viewer/net/specify-cad-rendering-options/)।

```csharp
public class CadOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BackgroundColor](../../groupdocs.viewer.options/cadoptions/backgroundcolor) { get; set; } | छवि पृष्ठभूमि रंग। |
| [EnablePerformanceConversionMode](../../groupdocs.viewer.options/cadoptions/enableperformanceconversionmode) { get; set; } | `true` पर इस फ़्लैग को सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन‑उन्मुख रूपांतरण मोड सक्रिय हो जाता है — इस मोड में रूपांतरण गति बहुत तेज़ होती है, लेकिन परिणामी दस्तावेज़ों की गुणवत्ता उल्लेखनीय रूप से खराब हो जाती है। डिफ़ॉल्ट रूप से यह निष्क्रिय रहता है (`false`) — परिणामी दस्तावेज़ों की गुणवत्ता प्रदर्शन की कीमत पर संभव सर्वोत्तम रहती है। |
| [Height](../../groupdocs.viewer.options/cadoptions/height) { get; } | आउटपुट परिणाम की ऊँचाई (पिक्सेल में)। |
| [Layers](../../groupdocs.viewer.options/cadoptions/layers) { get; set; } | रेंडर करने के लिए CAD ड्रॉइंग लेयर्स। |
| [LayoutName](../../groupdocs.viewer.options/cadoptions/layoutname) { get; set; } | रेंडर करने के लिए विशिष्ट लेआउट का नाम। लेआउट नाम केस‑सेंसिटिव है। |
| [Pc3File](../../groupdocs.viewer.options/cadoptions/pc3file) { get; set; } | PC3 - प्लॉटर कॉन्फ़िगरेशन फ़ाइल |
| [RenderLayouts](../../groupdocs.viewer.options/cadoptions/renderlayouts) { get; set; } | फ़्लैग यदि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए। |
| [ScaleFactor](../../groupdocs.viewer.options/cadoptions/scalefactor) { get; } | 1 से अधिक मान आउटपुट परिणाम को बड़ा करता है; 0 और 1 के बीच का मान आउटपुट परिणाम को घटाता है। |
| [Tiles](../../groupdocs.viewer.options/cadoptions/tiles) { get; set; } | रेंडर करने के लिए ड्राइंग क्षेत्रों। |
| [Width](../../groupdocs.viewer.options/cadoptions/width) { get; } | आउटपुट परिणाम की चौड़ाई (पिक्सेल में)। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ForRenderingByHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbyheight)(int) | ऊँचाई द्वारा रेंडरिंग के लिए [`CadOptions`](../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingByScaleFactor](../../groupdocs.viewer.options/cadoptions/forrenderingbyscalefactor)(float) | स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए [`CadOptions`](../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingByWidth](../../groupdocs.viewer.options/cadoptions/forrenderingbywidth)(int) | चौड़ाई द्वारा रेंडरिंग के लिए [`CadOptions`](../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingByWidthAndHeight](../../groupdocs.viewer.options/cadoptions/forrenderingbywidthandheight)(int, int) | चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए [`CadOptions`](../cadoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
