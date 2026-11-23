---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer के लिए .NET API Reference"
description: "स्प्रेडशीट रेंडर करने के विकल्प शामिल करता है। विवरण के लिए Render spreadsheet fileshttps//docs.groupdocs.com/viewer/net/renderspreadsheets/ टॉपिक के चाइल्ड देखें।"
type: docs
weight: 530
url: /hi/net/groupdocs.viewer.options/spreadsheetoptions/
---

## SpreadsheetOptions class

स्प्रेडशीट फ़ाइलों को रेंडर करने के विकल्प शामिल हैं। विवरण के लिए, देखें [स्प्रेडशीट फ़ाइलों को रेंडर करें](https://docs.groupdocs.com/viewer/net/render-spreadsheets/) विषय के चाइल्ड।

```csharp
public class SpreadsheetOptions
```

## गुण

| नाम | विवरण |
| --- | --- |
| [BottomMargin](../../groupdocs.viewer.options/spreadsheetoptions/bottommargin) { get; set; } | PDF में कनवर्ट करते समय पृष्ठ के नीचे के मार्जिन को सेट करता है। |
| [CountColumnsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countcolumnsperpage) { get; } | वर्कशीट को पृष्ठों में विभाजित करते समय प्रत्येक पृष्ठ पर शामिल करने के लिए कॉलमों की संख्या। |
| [CountRowsPerPage](../../groupdocs.viewer.options/spreadsheetoptions/countrowsperpage) { get; } | वर्कशीट को पृष्ठों में विभाजित करते समय प्रत्येक पृष्ठ पर शामिल करने के लिए पंक्तियों की संख्या। |
| [DetectSeparator](../../groupdocs.viewer.options/spreadsheetoptions/detectseparator) { get; set; } | सेपरेटर का पता लगाएँ (CSV/TSV फ़ाइलों के लिए)। |
| [HorizontalResolution](../../groupdocs.viewer.options/spreadsheetoptions/horizontalresolution) { get; set; } | जनरेटेड इमेज़ की क्षैतिज रिज़ॉल्यूशन को डॉट्स पर इंच में प्राप्त करता है या सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है। |
| [LeftMargin](../../groupdocs.viewer.options/spreadsheetoptions/leftmargin) { get; set; } | PDF में कनवर्ट करते समय पृष्ठ के बाएँ मार्जिन को सेट करता है। |
| [RenderGridLines](../../groupdocs.viewer.options/spreadsheetoptions/rendergridlines) { get; set; } | ग्रिड लाइनों के रेंडरिंग को सक्षम करता है। |
| [RenderHeadings](../../groupdocs.viewer.options/spreadsheetoptions/renderheadings) { get; set; } | हेडिंग्स के रेंडरिंग को सक्षम करता है। |
| [RenderHiddenColumns](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddencolumns) { get; set; } | छिपे हुए कॉलमों के रेंडरिंग को सक्षम करता है। |
| [RenderHiddenRows](../../groupdocs.viewer.options/spreadsheetoptions/renderhiddenrows) { get; set; } | छिपी हुई पंक्तियों के रेंडरिंग को सक्षम करता है। |
| [RightMargin](../../groupdocs.viewer.options/spreadsheetoptions/rightmargin) { get; set; } | PDF में कनवर्ट करते समय पृष्ठ के दाएँ मार्जिन को सेट करता है। |
| [SkipEmptyColumns](../../groupdocs.viewer.options/spreadsheetoptions/skipemptycolumns) { get; set; } | खाली कॉलमों के रेंडरिंग को अक्षम करता है। |
| [SkipEmptyRows](../../groupdocs.viewer.options/spreadsheetoptions/skipemptyrows) { get; set; } | खाली पंक्तियों के रेंडरिंग को अक्षम करता है। |
| [TextOverflowMode](../../groupdocs.viewer.options/spreadsheetoptions/textoverflowmode) { get; set; } | स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड सेट करता है। डिफ़ॉल्ट रूप से , है, जो डिफ़ॉल्ट MS Excel व्यवहार की नकल करता है। |
| [TopMargin](../../groupdocs.viewer.options/spreadsheetoptions/topmargin) { get; set; } | PDF में बदलते समय पृष्ठ का शीर्ष मार्जिन सेट करता है। |
| [VerticalResolution](../../groupdocs.viewer.options/spreadsheetoptions/verticalresolution) { get; set; } | उत्पन्न छवियों के लिए डॉट्स प्रति इंच में ऊर्ध्वाधर रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है। |

## विधियाँ

| नाम | विवरण |
| --- | --- |
| static [ForOnePagePerSheet](../../groupdocs.viewer.options/spreadsheetoptions/foronepagepersheet)() | पूरे शीट को एक पृष्ठ में रेंडर करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingByPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingbypagebreaks)() | पेज ब्रेक द्वारा पृष्ठों में विभाजित करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingPrintArea](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintarea)() | केवल प्रिंट क्षेत्रों को रेंडर करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForRenderingPrintAreaAndPageBreaks](../../groupdocs.viewer.options/spreadsheetoptions/forrenderingprintareaandpagebreaks)() | प्रिंट क्षेत्रों और पेज ब्रेक को रेंडर करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages)(int) | शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |
| static [ForSplitSheetIntoPages](../../groupdocs.viewer.options/spreadsheetoptions/forsplitsheetintopages#forsplitsheetintopages_1)(int, int) | शीट को पृष्ठों में रेंडर करने के लिए [`SpreadsheetOptions`](../spreadsheetoptions) क्लास का एक इंस्टेंस इनिशियलाइज़ करता है। |

### संबंधित देखें

* namespace [GroupDocs.Viewer.Options](../../groupdocs.viewer.options)
* assembly [GroupDocs.Viewer](../../)

<!-- संपादित न करें: xmldocmd द्वारा GroupDocs.Viewer.dll के लिए उत्पन्न -->
