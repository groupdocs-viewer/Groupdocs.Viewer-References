---
title: HtmlViewOptions
second_title: .NET API संदर्भ के लिए GroupDocs.Viewer
description: HTML प्ररूप में दस्तवेज़ प्रस्तुत करने के लए वकल्प प्रदन करत है
type: docs
weight: 330
url: /hi/net/groupdocs.viewer.options/htmlviewoptions/
---
## HtmlViewOptions class

HTML प्रारूप में दस्तावेज़ प्रस्तुत करने के लिए विकल्प प्रदान करता है।

```csharp
public class HtmlViewOptions : ViewOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | संग्रह फ़ाइलें विकल्प देखें। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | सीएडी आरेखण दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | डिफ़ॉल्ट फ़ॉन्ट का उपयोग तब किया जाता है जब दस्तावेज़ में उपयोग किया गया विशेष फ़ॉन्ट नहीं मिल पाता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेश विकल्प देखें। |
| [ExcludeFonts](../../groupdocs.viewer.options/htmlviewoptions/excludefonts) { get; set; } | सक्षम होने पर HTML दस्तावेज़ में किसी भी फ़ॉन्ट को जोड़ने से रोकता है। |
| [FontsToExclude](../../groupdocs.viewer.options/htmlviewoptions/fontstoexclude) { get; set; } | फ़ॉन्ट नामों की सूची, HTML दस्तावेज़ से बाहर करने के लिए. |
| [ForPrinting](../../groupdocs.viewer.options/htmlviewoptions/forprinting) { get; set; } | इंगित करता है कि प्रिंटिंग के लिए आउटपुट एचटीएमएल को अनुकूलित करना है या नहीं। |
| [ImageHeight](../../groupdocs.viewer.options/htmlviewoptions/imageheight) { get; set; } | पिक्सेल में आउटपुट इमेज की ऊंचाई। (एक छवि को केवल HTML में कनवर्ट करते समय) |
| [ImageMaxHeight](../../groupdocs.viewer.options/htmlviewoptions/imagemaxheight) { get; set; } | पिक्सल में आउटपुट छवि की अधिकतम ऊंचाई। (एक छवि को केवल HTML में कनवर्ट करते समय) |
| [ImageMaxWidth](../../groupdocs.viewer.options/htmlviewoptions/imagemaxwidth) { get; set; } | पिक्सल में आउटपुट छवि की अधिकतम चौड़ाई। (एक छवि को केवल HTML में कनवर्ट करते समय) |
| [ImageWidth](../../groupdocs.viewer.options/htmlviewoptions/imagewidth) { get; set; } | पिक्सल में आउटपुट छवि की चौड़ाई। (एक छवि को केवल HTML में कनवर्ट करते समय) |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल संग्रहण डेटा फ़ाइलें दृश्य विकल्प. |
| [Minify](../../groupdocs.viewer.options/htmlviewoptions/minify) { get; set; } | HTML सामग्री और HTML संसाधनों को कम करने में सक्षम बनाता है। |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | एमएस आउटलुक डेटा फ़ाइलें विकल्प देखें। |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | पीडीएफ दस्तावेज़ विकल्प देखें। |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | प्रस्तुति प्रसंस्करण दस्तावेज़ विकल्प देखें। |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | परियोजना प्रबंधन फ़ाइलें विकल्प देखें। |
| [RenderComments](../../groupdocs.viewer.options/baseviewoptions/rendercomments) { get; set; } | टिप्पणियां प्रस्तुत करना सक्षम करता है. |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | छिपे हुए पेजों की रेंडरिंग सक्षम करता है. |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | नोट्स प्रस्तुत करना सक्षम करता है। |
| [RenderResponsive](../../groupdocs.viewer.options/htmlviewoptions/renderresponsive) { get; set; } | उत्तरदायी प्रतिपादन सक्षम करता है; उत्तरदायी वेब-पृष्ठ विभिन्न स्क्रीन आकार वाले उपकरणों पर अच्छी तरह से प्रस्तुत होते हैं। |
| [RenderToSinglePage](../../groupdocs.viewer.options/htmlviewoptions/rendertosinglepage) { get; set; } | संपूर्ण दस्तावेज़ को एक HTML फ़ाइल में रेंडर करने में सक्षम बनाता है. |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | स्प्रैडशीट फ़ाइलें देखने के विकल्प. |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | पाठ फ़ाइलें पेज विकल्पों में विभाजित हो रही हैं। |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | दस्तावेज़ों को संसाधित करने वाली Visio फ़ाइलें विकल्प देखें। |
| [Watermark](../../groupdocs.viewer.options/viewoptions/watermark) { get; set; } | टेक्स्ट वॉटरमार्क प्रत्येक पृष्ठ पर लागू होता है। |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | यह रेंडरिंग विकल्प आपको वेब दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | यह रेंडरिंग विकल्प आपको Word दस्तावेज़ों को रेंडर करते समय आउटपुट HTML/PDF/PNG/JPEG के स्वरूप को अनुकूलित करने में सक्षम बनाता है। |

## तरीकों

| नाम | विवरण |
| --- | --- |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources)() | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) वर्ग. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_1)(CreatePageStream) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) एम्बेड किए गए संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_3)(IPageStreamFactory) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) एम्बेड किए गए संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_4)(string) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) वर्ग. |
| static [ForEmbeddedResources](../../groupdocs.viewer.options/htmlviewoptions/forembeddedresources#forembeddedresources_2)(CreatePageStream, ReleasePageStream) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) एम्बेड किए गए संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources)() | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) वर्ग. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_3)(IPageStreamFactory, IResourceStreamFactory) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_1)(CreatePageStream, CreateResourceStream, CreateResourceUrl) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_4)(string, string, string) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) वर्ग. |
| static [ForExternalResources](../../groupdocs.viewer.options/htmlviewoptions/forexternalresources#forexternalresources_2)(CreatePageStream, CreateResourceStream, CreateResourceUrl, ReleasePageStream, ReleaseResourceStream) | का नया उदाहरण शुरू करता है[`HtmlViewOptions`](../htmlviewoptions) बाहरी संसाधनों के साथ HTML में रेंडर करने के लिए क्लास. |
| [RotatePage](../../groupdocs.viewer.options/viewoptions/rotatepage)(int, Rotation) | पृष्ठ पर दक्षिणावर्त घुमाव लागू करता है। |

## खेत

| नाम | विवरण |
| --- | --- |
| readonly [PageRotations](../../groupdocs.viewer.options/viewoptions/pagerotations) | पेज रोटेशन. |

### यह सभी देखें

* class [ViewOptions](../viewoptions)
* नाम स्थान [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* सभा [GroupDocs.Viewer](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Viewer.dll -->
