---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "स्प्रेडशीट को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 31
url: /hi/nodejs-java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

स्प्रेडशीट को रेंडर करने के विकल्प प्रदान करता है।

SpreadsheetOptions वर्ग विभिन्न सेटिंग्स और पैरामीटरों को समाहित करता है जिन्हें GroupDocs.Viewer घटक में स्प्रेडशीट फ़ाइलों (जैसे Excel या CSV फ़ाइलें) के रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है। विवरण के लिए, [Render spreadsheet files][] विषय की चाइल्ड्स देखें।

उदाहरण उपयोग:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```


[Render spreadsheet files]: https://docs.groupdocs.com/viewer/java/render-spreadsheets/
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [isRenderByPageBreaks()](#isRenderByPageBreaks--) | निर्धारित करता है कि क्या कार्यपत्रक को पृष्ठ विभाजनों द्वारा रेंडर किया जाना चाहिए। |
| [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | निर्धारित करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं। |
| [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाता है। |
| [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | निर्धारित करता है कि CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाया जाए या नहीं। |
| [forOnePagePerSheet()](#forOnePagePerSheet--) | एक शीट को एक पेज में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस बनाता है। |
| [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | एक शीट को कई पेजों में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस बनाता है। |
| [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | शीट को पेजों में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [forRenderingPrintArea()](#forRenderingPrintArea--) | केवल प्रिंट एरिया को रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [isOnePagePerSheet()](#isOnePagePerSheet--) | यह दर्शाता है कि एक शीट को एक पेज में रेंडर किया गया है या नहीं। |
| [getCountRowsPerPage()](#getCountRowsPerPage--) | वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए पंक्तियों की संख्या प्राप्त करता है। |
| [getCountColumnsPerPage()](#getCountColumnsPerPage--) | वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए कॉलम की संख्या प्राप्त करता है। |
| [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए कॉलम की संख्या निर्धारित करता है। |
| [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | यह दर्शाता है कि केवल प्रिंट एरिया रेंडर किए गए हैं या नहीं। |
| [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | जब यह विकल्प सक्षम किया जाता है, तो वर्कशीट को प्रिंट एरिया के भीतर पड़ने वाले पेज ब्रेक द्वारा रेंडर किया जाएगा। |
| [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | निर्धारित करता है कि वर्कशीट को प्रिंट एरिया के भीतर पड़ने वाले पेज ब्रेक द्वारा रेंडर किया जाए या नहीं। |
| [isRenderGridLines()](#isRenderGridLines--) | ग्रिड लाइनों के रेंडरिंग को सक्षम करता है। |
| [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | ग्रिड लाइनों के रेंडरिंग को सक्षम या अक्षम करता है। |
| [isSkipEmptyRows()](#isSkipEmptyRows--) | यह दर्शाता है कि रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं। |
| [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | निर्धारित करता है कि रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं। |
| [isSkipEmptyColumns()](#isSkipEmptyColumns--) | यह दर्शाता है कि रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं। |
| [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | निर्धारित करता है कि रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं। |
| [isRenderHiddenRows()](#isRenderHiddenRows--) | निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाना चाहिए या नहीं। |
| [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाए या नहीं। |
| [isRenderHeadings()](#isRenderHeadings--) | जाँचता है कि हेडिंग्स का रेंडरिंग सक्षम है या नहीं। |
| [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | हेडिंग्स के रेंडरिंग को सक्षम करता है। |
| [isRenderHiddenColumns()](#isRenderHiddenColumns--) | छिपे कॉलम के रेंडरिंग को सक्षम करता है। |
| [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | छिपे कॉलम के रेंडरिंग को सक्षम करता है। |
| [getTextOverflowMode()](#getTextOverflowMode--) | स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड लौटाता है। |
| [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड सेट करता है। |
| [getLeftMargin()](#getLeftMargin--) | PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। |
| [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। |
| [getRightMargin()](#getRightMargin--) | PDF में परिवर्तित करते समय वर्कशीट का दायाँ मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [setRightMargin(double rightMargin)](#setRightMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का दायाँ मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [getTopMargin()](#getTopMargin--) | PDF में परिवर्तित करते समय वर्कशीट का ऊपर का मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [setTopMargin(double topMargin)](#setTopMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का ऊपर का मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [getBottomMargin()](#getBottomMargin--) | PDF में परिवर्तित करते समय वर्कशीट का नीचे का मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का नीचे का मार्जिन सेट करने के लिए, यदि पैरामीटर 0 से कम है तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
| [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | प्रिंट एरिया और पेज ब्रेक्स को रेंडर करने के लिए SpreadsheetOptions का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | केवल प्रिंट एरिया को रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


निर्धारित करता है कि क्या कार्यपत्रक को पृष्ठ विभाजनों द्वारा रेंडर किया जाना चाहिए।

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Returns:**
boolean - true यदि वर्कशीट को पेज ब्रेक्स द्वारा रेंडर किया जाना चाहिए, अन्यथा false।
### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


निर्धारित करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं।

***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderByPageBreaks | boolean | true यदि वर्कशीट को पेज ब्रेक्स द्वारा रेंडर किया जाना चाहिए, अन्यथा false। |

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Returns:**
boolean - true यदि विभाजक को स्वचालित रूप से पता लगाया जाना चाहिए, अन्यथा false।
### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


निर्धारित करता है कि CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाया जाए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| detectSeparator | boolean | true विभाजक को स्वचालित रूप से पता लगाने के लिए, अन्यथा false। |

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


एक शीट को एक पेज में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस बनाता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.
### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


एक शीट को कई पेजों में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस बनाता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| countRowsPerPage | int | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.
### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


शीट को पेजों में रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| countRowsPerPage | int | प्रत्येक पृष्ठ पर शामिल करने के लिए पंक्तियों की संख्या। |
| countColumnsPerPage | int | प्रत्येक पृष्ठ पर शामिल करने के लिए कॉलम की संख्या। |

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.
### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


केवल प्रिंट एरिया को रेंडर करने के लिए SpreadsheetOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.
### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


यह दर्शाता है कि एक शीट को एक पेज में रेंडर किया गया है या नहीं।

**Returns:**
boolean - true यदि एक शीट को एक पृष्ठ में रेंडर किया जाता है; अन्यथा false।
### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए पंक्तियों की संख्या प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows

**Returns:**
int - प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की गिनती।
### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए कॉलम की संख्या प्राप्त करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Returns:**
int - प्रत्येक पृष्ठ में शामिल करने के लिए कॉलम की गिनती।
### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए कॉलम की संख्या निर्धारित करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| countColumnsPerPage | int | प्रत्येक पृष्ठ में शामिल करने के लिए कॉलम की गिनती। |

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


यह दर्शाता है कि केवल प्रिंट एरिया रेंडर किए गए हैं या नहीं।

**Returns:**
boolean - true यदि केवल प्रिंट एरिया रेंडर किए जाते हैं, अन्यथा false।
### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


जब यह विकल्प सक्षम किया जाता है, तो वर्कशीट को प्रिंट एरिया के भीतर पड़ने वाले पेज ब्रेक द्वारा रेंडर किया जाएगा।

**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


निर्धारित करता है कि वर्कशीट को प्रिंट एरिया के भीतर पड़ने वाले पेज ब्रेक द्वारा रेंडर किया जाए या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderingPrintAreaAndPageBreaks | boolean | सक्षम करने के लिए true सेट करें, अक्षम करने के लिए false। |

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


ग्रिड लाइनों के रेंडरिंग को सक्षम करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Returns:**
boolean -  true  यदि ग्रिड लाइनों को सक्षम किया गया है,  false  अन्यथा।
### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


ग्रिड लाइनों के रेंडरिंग को सक्षम या अक्षम करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  ग्रिड लाइनों के रेंडरिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


यह दर्शाता है कि रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  यदि खाली पंक्तियों को छोड़ना चाहिए,  false  अन्यथा।
### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


निर्धारित करता है कि रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  खाली पंक्तियों को छोड़ने के लिए,  false  अन्यथा। |

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


यह दर्शाता है कि रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Returns:**
boolean -  true  यदि खाली कॉलम छोड़े जाएँ,  false  अन्यथा।
### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


निर्धारित करता है कि रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  खाली कॉलम को छोड़ने के लिए,  false  अन्यथा। |

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाना चाहिए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  यदि छिपी पंक्तियों को रेंडर किया जाना चाहिए,  false  अन्यथा।
### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाए या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  छिपी पंक्तियों के रेंडरिंग को सक्षम करने के लिए,  false  इसे अक्षम करने के लिए। |

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


जाँचता है कि हेडिंग्स का रेंडरिंग सक्षम है या नहीं।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Returns:**
boolean -  true  यदि हेडिंग्स का रेंडरिंग सक्षम है,  false  अन्यथा।
### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


हेडिंग्स के रेंडरिंग को सक्षम करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| renderHeadings | boolean | true  हेडिंग्स के रेंडरिंग को सक्षम करने के लिए,  false  अक्षम करने के लिए। |

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


छिपे कॉलम के रेंडरिंग को सक्षम करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Returns:**
boolean -  true  यदि छिपे कॉलम का रेंडरिंग सक्षम है,  false  अन्यथा।
### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


छिपे कॉलम के रेंडरिंग को सक्षम करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  छिपे कॉलम के रेंडरिंग को सक्षम करने के लिए,  false  अक्षम करने के लिए। |

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड लौटाता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.
### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड सेट करता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | सेट किया जाने वाला टेक्स्ट ओवरफ़्लो मोड। |

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है।

यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है।

यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


वर्कशीट को PDF में बदलते समय दाएँ मार्जिन को सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


वर्कशीट को PDF में बदलते समय दाएँ मार्जिन को सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


वर्कशीट को PDF में बदलते समय शीर्ष मार्जिन सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


वर्कशीट को PDF में बदलते समय शीर्ष मार्जिन सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


वर्कशीट को PDF में बदलते समय नीचे का मार्जिन सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


वर्कशीट को PDF में बदलते समय नीचे का मार्जिन सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| bottomMargin | double |  |

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


प्रिंट एरिया और पेज ब्रेक्स को रेंडर करने के लिए  SpreadsheetOptions  का नया इंस्टेंस इनिशियलाइज़ करता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.
### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


केवल प्रिंट एरिया को रेंडर करने के लिए  SpreadsheetOptions  क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.
