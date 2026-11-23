---
title: "ViewInfoOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "व्यू के बारे में जानकारी प्राप्त करने के विकल्प शामिल हैं।"
type: docs
weight: 580
url: /hi/net/groupdocs.viewer.options/viewinfooptions/
---

## ViewInfoOptions class

व्यू के बारे में जानकारी प्राप्त करने के विकल्प शामिल हैं।

```csharp
public class ViewInfoOptions : BaseViewOptions, IMaxSizeOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [ArchiveOptions](../../groupdocs.viewer.options/baseviewoptions/archiveoptions) { get; set; } | आर्काइव फ़ाइलों के दृश्य विकल्प। |
| [CadOptions](../../groupdocs.viewer.options/baseviewoptions/cadoptions) { get; set; } | CAD ड्राइंग के दृश्य विकल्प। |
| [DefaultFontName](../../groupdocs.viewer.options/baseviewoptions/defaultfontname) { get; set; } | दस्तावेज़ के लिए डिफ़ॉल्ट फ़ॉन्ट सेट करता है। |
| [EmailOptions](../../groupdocs.viewer.options/baseviewoptions/emailoptions) { get; set; } | ईमेल संदेशों के दृश्य विकल्प। |
| [ExtractText](../../groupdocs.viewer.options/viewinfooptions/extracttext) { get; set; } | टेक्स्ट एक्सट्रैक्शन सक्षम करता है। |
| [Height](../../groupdocs.viewer.options/viewinfooptions/height) { get; set; } | आउटपुट इमेज की ऊँचाई (पिक्सेल में, केवल PNG/JPG रेंडरिंग के लिए)। |
| [MailStorageOptions](../../groupdocs.viewer.options/baseviewoptions/mailstorageoptions) { get; set; } | मेल स्टोरेज डेटा फ़ाइलों के दृश्य विकल्प। |
| [MaxHeight](../../groupdocs.viewer.options/viewinfooptions/maxheight) { get; set; } | आउटपुट इमेज की अधिकतम ऊँचाई सेट करता है (पिक्सेल में, केवल PNG/JPG रेंडरिंग के लिए)। |
| [MaxWidth](../../groupdocs.viewer.options/viewinfooptions/maxwidth) { get; set; } | आउटपुट इमेज की अधिकतम चौड़ाई सेट करता है (पिक्सेल में, केवल PNG/JPG रेंडरिंग के लिए)। |
| [OutlookOptions](../../groupdocs.viewer.options/baseviewoptions/outlookoptions) { get; set; } | Microsoft Outlook डेटा फ़ाइलों के दृश्य विकल्प। |
| [PdfOptions](../../groupdocs.viewer.options/baseviewoptions/pdfoptions) { get; set; } | PDF दस्तावेज़ के दृश्य विकल्प। |
| [PresentationOptions](../../groupdocs.viewer.options/baseviewoptions/presentationoptions) { get; set; } | प्रेजेंटेशन फ़ाइलों के दृश्य विकल्प। |
| [ProjectManagementOptions](../../groupdocs.viewer.options/baseviewoptions/projectmanagementoptions) { get; set; } | प्रोजेक्ट मैनेजमेंट फ़ाइलों के दृश्य विकल्प। |
| [RemoveComments](../../groupdocs.viewer.options/baseviewoptions/removecomments) { get; set; } | जब `true` पर सेट किया जाता है तो टिप्पणी रेंडरिंग को निष्क्रिय करता है। डिफ़ॉल्ट रूप से यह `false` है — सभी टिप्पणियाँ प्रदर्शित होती हैं। |
| [RenderHiddenPages](../../groupdocs.viewer.options/baseviewoptions/renderhiddenpages) { get; set; } | छिपे पृष्ठों की रेंडरिंग को सक्षम करता है। |
| [RenderNotes](../../groupdocs.viewer.options/baseviewoptions/rendernotes) { get; set; } | कुछ फ़ॉर्मैट्स के लिए नोट्स और एनोटेशन की रेंडरिंग को सक्षम करता है। |
| [SpreadsheetOptions](../../groupdocs.viewer.options/baseviewoptions/spreadsheetoptions) { get; set; } | स्प्रेडशीट फ़ाइलों के दृश्य विकल्प। |
| [TextOptions](../../groupdocs.viewer.options/baseviewoptions/textoptions) { get; set; } | टेक्स्ट फ़ाइलों के दृश्य विकल्प। |
| [VisioRenderingOptions](../../groupdocs.viewer.options/baseviewoptions/visiorenderingoptions) { get; set; } | Visio फ़ाइलों के दृश्य विकल्प। |
| [WebDocumentOptions](../../groupdocs.viewer.options/baseviewoptions/webdocumentoptions) { get; set; } | वेब फ़ाइलों के दृश्य विकल्प। |
| [Width](../../groupdocs.viewer.options/viewinfooptions/width) { get; set; } | आउटपुट इमेज की चौड़ाई (पिक्सेल में, केवल PNG/JPG रेंडरिंग के लिए)। |
| [WordProcessingOptions](../../groupdocs.viewer.options/baseviewoptions/wordprocessingoptions) { get; set; } | वर्ड प्रोसेसिंग फ़ाइलों के दृश्य विकल्प। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview)() | HTML में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForHtmlView](../../groupdocs.viewer.options/viewinfooptions/forhtmlview#forhtmlview_1)(bool) | HTML में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview)() | JPG में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForJpgView](../../groupdocs.viewer.options/viewinfooptions/forjpgview#forjpgview_1)(bool) | JPG में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForPdfView](../../groupdocs.viewer.options/viewinfooptions/forpdfview)() | PDF में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview)() | PNG में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [ForPngView](../../groupdocs.viewer.options/viewinfooptions/forpngview#forpngview_1)(bool) | PNG में render करते समय view के बारे में जानकारी प्राप्त करने के लिए [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [FromHtmlViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromhtmlviewoptions)(HtmlViewOptions) | [`HtmlViewOptions`](../htmlviewoptions) ऑब्जेक्ट के आधार पर [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [FromJpgViewOptions](../../groupdocs.viewer.options/viewinfooptions/fromjpgviewoptions)(JpgViewOptions) | [`JpgViewOptions`](../jpgviewoptions) ऑब्जेक्ट के आधार पर [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [FromPdfViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompdfviewoptions)(PdfViewOptions) | [`PdfViewOptions`](../pdfviewoptions) ऑब्जेक्ट के आधार पर [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |
| static [FromPngViewOptions](../../groupdocs.viewer.options/viewinfooptions/frompngviewoptions)(PngViewOptions) | [`PngViewOptions`](../pngviewoptions) ऑब्जेक्ट के आधार पर [`ViewInfoOptions`](../viewinfooptions) क्लास का एक instance initialize करता है। |

### संबंधित देखें

* class [BaseViewOptions](../baseviewoptions)
* interface [IMaxSizeOptions](../imaxsizeoptions)
* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
