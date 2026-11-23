---
title: "HtmlViewOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "दस्तावेज़ों को HTML फ़ॉर्मेट में रेंडर करने के विकल्प शामिल हैं। विवरण के लिए टॉपिक https//docs.groupdocs.com/viewer/net/renderingtohtml/ और उसके चाइल्ड देखें।"
type: docs
weight: 320
url: /hi/net/groupdocs.viewer.options/htmlviewoptions/
---

## HtmlViewOptions class

दस्तावेज़ों को HTML फ़ॉर्मेट में रेंडर करने के विकल्प शामिल हैं। विवरण के लिए, देखें [विषय](https://docs.groupdocs.com/viewer/net/rendering-to-html/) और इसके चाइल्ड।

```csharp
public class HtmlViewOptions : ViewOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | आर्काइव फ़ाइलों के दृश्य विकल्प। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD ड्राइंग के दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेशों के दृश्य विकल्प। |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | HTML दस्तावेज़ में किसी भी फ़ॉन्ट को जोड़ने को अक्षम करता है। |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | HTML दस्तावेज़ से बाहर रखने के लिए फ़ॉन्ट नामों की सूची। |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | प्रिंटिंग के लिए आउटपुट HTML को अनुकूलित करने को सक्षम करता है। |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | आउटपुट इमेज की ऊँचाई (पिक्सेल में)। यह प्रॉपर्टी केवल एकल इमेज को HTML में बदलते समय उपलब्ध है। |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | आउटपुट छवि की अधिकतम ऊँचाई (पिक्सेल में)। यह प्रॉपर्टी केवल एकल छवि को HTML में परिवर्तित करते समय उपलब्ध है। |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | आउटपुट छवि की अधिकतम चौड़ाई (पिक्सेल में)। यह प्रॉपर्टी केवल एकल छवि को HTML में परिवर्तित करते समय उपलब्ध है। |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | आउटपुट छवि की चौड़ाई (पिक्सेल में)। यह प्रॉपर्टी केवल एकल छवि को HTML में परिवर्तित करते समय उपलब्ध है। |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प। |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML सामग्री और HTML संसाधनों का संक्षिप्तकरण सक्षम करता है। |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook डेटा फ़ाइलों के दृश्य विकल्प। |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF दस्तावेज़ के दृश्य विकल्प। |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | प्रेजेंटेशन फ़ाइलों के दृश्य विकल्प। |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प। |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | जब `true` पर सेट किया जाता है तो टिप्पणी रेंडरिंग को निष्क्रिय करता है। डिफ़ॉल्ट रूप से यह `false` है — सभी टिप्पणियाँ प्रदर्शित होती हैं। |
| [RemoveJavaScript](../../groupdocs.viewer.options/htmlviewoptions/removejavascript) { get; set; } | इनपुट दस्तावेज़ों को रेंडर करते समय, जिनमें स्क्रिप्ट्स हैं, परिणामस्वरूप HTML दस्तावेज़ों में लिंक से JavaScript स्रोत कोड को हटाने की अनुमति देता है। डिफ़ॉल्ट रूप से यह सक्षम है (`true`). |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | छिपे पृष्ठों की रेंडरिंग को सक्षम करता है। |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | कुछ फ़ॉर्मैट्स के लिए नोट्स और एनोटेशन की रेंडरिंग को सक्षम करता है। |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | रिस्पॉन्सिव रेंडरिंग सक्षम करता है। |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | पूरे दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने को सक्षम करता है। |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प। |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | टेक्स्ट फ़ाइलों के दृश्य विकल्प। |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio फ़ाइलों के दृश्य विकल्प। |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | प्रत्येक पृष्ठ पर लागू किया जाने वाला टेक्स्ट वॉटरमार्क। |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | वेब फ़ाइलों के दृश्य विकल्प। |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | एम्बेडेड रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | एम्बेडेड रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | एम्बेडेड रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | एक्सटर्नल रिसोर्सेज़ के साथ HTML में रेंडर करने के लिए [`HtmlViewOptions`](../htmlviewoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | एक पृष्ठ पर घड़ी की दिशा में घुमाव लागू करता है। |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | पृष्ठ घुमाव। |

### संबंधित देखें

* class [ViewOptions](../viewoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
