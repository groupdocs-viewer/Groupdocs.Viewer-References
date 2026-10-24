---
title: "SpreadsheetOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "स्प्रेडशीट को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 31
url: /hi/java/com.groupdocs.viewer.options/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object
```
public class SpreadsheetOptions
```

स्प्रेडशीट को रेंडर करने के विकल्प प्रदान करता है।


SpreadsheetOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में स्प्रेडशीट फ़ाइलों (जैसे Excel या CSV फ़ाइलें) की रेंडरिंग को नियंत्रित करने के लिए।
विवरण के लिए, देखें [Render spreadsheet files](../https://docs.groupdocs.com/viewer/java/render-spreadsheets/) विषय के उपविषय।


उदाहरण उपयोग:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 SpreadsheetOptions spreadsheetOptions = pngViewOptions.getSpreadsheetOptions();
 spreadsheetOptions.setRenderHeadings(true);
 spreadsheetOptions.setCountColumnsPerPage(24);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Methods

| Method | विवरण |
| --- | --- |
|  | [isRenderByPageBreaks()](#isRenderByPageBreaks--) | निर्धारित करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं। |
|
|  | [setRenderByPageBreaks(boolean renderByPageBreaks)](#setRenderByPageBreaks-boolean-) | सेट करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं। |
|
|  | [isDetectSeparator()](#isDetectSeparator--) | CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाता है। |
|
|  | [setDetectSeparator(boolean detectSeparator)](#setDetectSeparator-boolean-) | सेट करता है कि CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाया जाए या नहीं। |
|
|  | [forOnePagePerSheet()](#forOnePagePerSheet--) | का एक नया उदाहरण बनाता है |
SpreadsheetOptions
एक शीट को एक पेज में रेंडर करने के लिए क्लास।
|
|  | [forSplitSheetIntoPages(int countRowsPerPage)](#forSplitSheetIntoPages-int-) | का एक नया उदाहरण बनाता है |
SpreadsheetOptions
एक शीट को कई पेजों में रेंडर करने के लिए क्लास।
|
|  | [forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)](#forSplitSheetIntoPages-int-int-) | नए उदाहरण को प्रारंभ करता है |
SpreadsheetOptions
एक शीट को पेजों में रेंडर करने के लिए क्लास।
|
|  | [forRenderingPrintArea()](#forRenderingPrintArea--) | नए उदाहरण को प्रारंभ करता है |
SpreadsheetOptions
केवल प्रिंट क्षेत्रों को रेंडर करने के लिए क्लास।
|
|  | [isOnePagePerSheet()](#isOnePagePerSheet--) | संकेत करता है कि एक शीट एक पेज में रेंडर की गई है या नहीं। |
|
|  | [getCountRowsPerPage()](#getCountRowsPerPage--) | वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए पंक्तियों की संख्या प्राप्त करता है। |
|
|  | [getCountColumnsPerPage()](#getCountColumnsPerPage--) | वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए स्तंभों की संख्या प्राप्त करता है। |
|
|  | [setCountColumnsPerPage(int countColumnsPerPage)](#setCountColumnsPerPage-int-) | वर्कशीट को पृष्ठों में विभाजित करते समय प्रत्येक पृष्ठ में शामिल करने के लिए कॉलम की संख्या निर्धारित करता है। |
|
|  | [isRenderPrintAreaOnly()](#isRenderPrintAreaOnly--) | यह दर्शाता है कि केवल प्रिंट क्षेत्रों को रेंडर किया जाए या नहीं। |
|
|  | [isRenderingPrintAreaAndPageBreaks()](#isRenderingPrintAreaAndPageBreaks--) | जब यह विकल्प सक्षम होता है, तो वर्कशीट को प्रिंट क्षेत्र के भीतर आने वाले पेज ब्रेक द्वारा रेंडर किया जाएगा। |
|
|  | [setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)](#setRenderingPrintAreaAndPageBreaks-boolean-) | प्रिंट क्षेत्र के भीतर आने वाले पेज ब्रेक द्वारा वर्कशीट को रेंडर करने की सेटिंग करता है। |
|
|  | [isRenderGridLines()](#isRenderGridLines--) | ग्रिड लाइनों का रेंडरिंग सक्षम करता है। |
|
|  | [setRenderGridLines(boolean value)](#setRenderGridLines-boolean-) | ग्रिड लाइनों के रेंडरिंग को सक्षम या अक्षम करता है। |
|
|  | [isSkipEmptyRows()](#isSkipEmptyRows--) | रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं, यह दर्शाता है। |
|
|  | [setSkipEmptyRows(boolean value)](#setSkipEmptyRows-boolean-) | रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं, यह सेट करता है। |
|
|  | [isSkipEmptyColumns()](#isSkipEmptyColumns--) | रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं, यह दर्शाता है। |
|
|  | [setSkipEmptyColumns(boolean value)](#setSkipEmptyColumns-boolean-) | रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं, यह सेट करता है। |
|
|  | [isRenderHiddenRows()](#isRenderHiddenRows--) | निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाना चाहिए या नहीं। |
|
|  | [setRenderHiddenRows(boolean value)](#setRenderHiddenRows-boolean-) | छिपी पंक्तियों को रेंडर करना चाहिए या नहीं, यह सेट करता है। |
|
|  | [isRenderHeadings()](#isRenderHeadings--) | जाँचता है कि हेडिंग्स का रेंडरिंग सक्षम है या नहीं। |
|
|  | [setRenderHeadings(boolean renderHeadings)](#setRenderHeadings-boolean-) | हेडिंग्स का रेंडरिंग सक्षम करता है। |
|
|  | [isRenderHiddenColumns()](#isRenderHiddenColumns--) | छिपे कॉलम का रेंडरिंग सक्षम करता है। |
|
|  | [setRenderHiddenColumns(boolean value)](#setRenderHiddenColumns-boolean-) | छिपे कॉलम का रेंडरिंग सक्षम करता है। |
|
|  | [getTextOverflowMode()](#getTextOverflowMode--) | स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड लौटाता है। |
|
|  | [setTextOverflowMode(TextOverflowMode value)](#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-) | स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड सेट करता है। |
|
|  | [getLeftMargin()](#getLeftMargin--) | PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। |
|
|  | [setLeftMargin(double leftMargin)](#setLeftMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। |
|
|  | [getRightMargin()](#getRightMargin--) | PDF में परिवर्तित करते समय वर्कशीट का दायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [setRightMargin(double rightMargin)](#setRightMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का दायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [getTopMargin()](#getTopMargin--) | PDF में परिवर्तित करते समय वर्कशीट का ऊपर का मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [setTopMargin(double topMargin)](#setTopMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का ऊपर का मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [getBottomMargin()](#getBottomMargin--) | PDF में परिवर्तित करते समय वर्कशीट का नीचे का मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [setBottomMargin(double bottomMargin)](#setBottomMargin-double-) | PDF में परिवर्तित करते समय वर्कशीट का नीचे का मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | जनरेट किए गए इमेज की क्षैतिज रेज़ोल्यूशन को डॉट्स प्रति इंच में प्राप्त या सेट करता है। |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | जनरेट किए गए इमेज की क्षैतिज रेज़ोल्यूशन को डॉट्स प्रति इंच में सेट करता है। |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | जनरेट किए गए इमेज की लंबवत रेज़ोल्यूशन को डॉट्स प्रति इंच में प्राप्त या सेट करता है। |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | जनरेट किए गए इमेज की लंबवत रेज़ोल्यूशन को डॉट्स प्रति इंच में सेट करता है। |
|
|  | [forRenderingPrintAreaAndPageBreaks()](#forRenderingPrintAreaAndPageBreaks--) | प्रिंट क्षेत्रों और पृष्ठ विभाजनों को रेंडर करने के लिए  SpreadsheetOptions  का नया उदाहरण प्रारंभ करता है। |
|
|  | [forRenderingByPageBreaks()](#forRenderingByPageBreaks--) | केवल प्रिंट क्षेत्रों को रेंडर करने के लिए  SpreadsheetOptions  क्लास का नया उदाहरण प्रारंभ करता है। |
|
### isRenderByPageBreaks() {#isRenderByPageBreaks--}
```
public boolean isRenderByPageBreaks()
```


निर्धारित करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं।


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Returns:**
boolean -  true  यदि वर्कशीट को पृष्ठ विभाजनों द्वारा रेंडर किया जाना चाहिए, अन्यथा  false।

### setRenderByPageBreaks(boolean renderByPageBreaks) {#setRenderByPageBreaks-boolean-}
```
public void setRenderByPageBreaks(boolean renderByPageBreaks)
```


सेट करता है कि वर्कशीट को पेज ब्रेक द्वारा रेंडर किया जाना चाहिए या नहीं।


***Note:** This option controls the rendering behavior of the worksheet, similar to printing a spreadsheet in Excel.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderByPageBreaks | boolean | true  यदि वर्कशीट को पृष्ठ विभाजनों द्वारा रेंडर किया जाना चाहिए, अन्यथा  false। |
|

### isDetectSeparator() {#isDetectSeparator--}
```
public boolean isDetectSeparator()
```


CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)।


**Returns:**
boolean -  true  यदि विभाजक को स्वचालित रूप से पहचाना जाना चाहिए, अन्यथा  false।

### setDetectSeparator(boolean detectSeparator) {#setDetectSeparator-boolean-}
```
public void setDetectSeparator(boolean detectSeparator)
```


सेट करता है कि CSV/TSV फ़ाइलों के लिए विभाजक का पता लगाया जाए या नहीं।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/#detect-a-csvtsv-separator)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | detectSeparator | boolean | true  स्वचालित रूप से विभाजक का पता लगाने के लिए, अन्यथा  false। |
|

### forOnePagePerSheet() {#forOnePagePerSheet--}
```
public static SpreadsheetOptions forOnePagePerSheet()
```


का एक नया उदाहरण बनाता है
SpreadsheetOptions
एक शीट को एक पेज में रेंडर करने के लिए क्लास।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-worksheet-on-one-page)।


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  class for rendering one sheet into one page.

### forSplitSheetIntoPages(int countRowsPerPage) {#forSplitSheetIntoPages-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage)
```


का एक नया उदाहरण बनाता है
SpreadsheetOptions
एक शीट को कई पेजों में रेंडर करने के लिए क्लास।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | countRowsPerPage | int | प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की संख्या। |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering a sheet into pages.

### forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage) {#forSplitSheetIntoPages-int-int-}
```
public static SpreadsheetOptions forSplitSheetIntoPages(int countRowsPerPage, int countColumnsPerPage)
```


नए उदाहरण को प्रारंभ करता है
SpreadsheetOptions
एक शीट को पेजों में रेंडर करने के लिए क्लास।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | countRowsPerPage | int | प्रत्येक पृष्ठ पर शामिल करने के लिए पंक्तियों की संख्या। |
|
|  | countColumnsPerPage | int | प्रत्येक पृष्ठ पर शामिल करने के लिए स्तंभों की संख्या। |
|

**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering a sheet into pages.

### forRenderingPrintArea() {#forRenderingPrintArea--}
```
public static SpreadsheetOptions forRenderingPrintArea()
```


नए उदाहरण को प्रारंभ करता है
SpreadsheetOptions
केवल प्रिंट क्षेत्रों को रेंडर करने के लिए क्लास।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-a-print-area)।


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of the  SpreadsheetOptions  class for rendering print areas only.

### isOnePagePerSheet() {#isOnePagePerSheet--}
```
public final boolean isOnePagePerSheet()
```


संकेत करता है कि एक शीट एक पेज में रेंडर की गई है या नहीं।


**Returns:**
boolean -  true  यदि एक शीट को एक पृष्ठ में रेंडर किया जाता है; अन्यथा  false।

### getCountRowsPerPage() {#getCountRowsPerPage--}
```
public final int getCountRowsPerPage()
```


वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए पंक्तियों की संख्या प्राप्त करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows)।


**Returns:**
int - प्रत्येक पृष्ठ में शामिल करने के लिए पंक्तियों की गिनती।

### getCountColumnsPerPage() {#getCountColumnsPerPage--}
```
public int getCountColumnsPerPage()
```


वर्कशीट को पेजों में विभाजित करते समय प्रत्येक पेज में शामिल करने के लिए स्तंभों की संख्या प्राप्त करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)।


**Returns:**
int - प्रत्येक पृष्ठ में शामिल करने के लिए स्तंभों की गिनती।

### setCountColumnsPerPage(int countColumnsPerPage) {#setCountColumnsPerPage-int-}
```
public void setCountColumnsPerPage(int countColumnsPerPage)
```


वर्कशीट को पृष्ठों में विभाजित करते समय प्रत्येक पृष्ठ में शामिल करने के लिए कॉलम की संख्या निर्धारित करता है।


विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#split-a-worksheet-into-pages-by-rows-and-columns)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | countColumnsPerPage | int | प्रत्येक पृष्ठ में शामिल करने के लिए स्तंभों की गिनती। |
|

### isRenderPrintAreaOnly() {#isRenderPrintAreaOnly--}
```
public final boolean isRenderPrintAreaOnly()
```


यह दर्शाता है कि केवल प्रिंट क्षेत्रों को रेंडर किया जाए या नहीं।


**Returns:**
boolean -  true  यदि केवल प्रिंट क्षेत्रों को रेंडर किया जाता है, अन्यथा  false।

### isRenderingPrintAreaAndPageBreaks() {#isRenderingPrintAreaAndPageBreaks--}
```
public boolean isRenderingPrintAreaAndPageBreaks()
```


जब यह विकल्प सक्षम होता है, तो वर्कशीट को प्रिंट क्षेत्र के भीतर आने वाले पेज ब्रेक द्वारा रेंडर किया जाएगा।


**Returns:**
boolean
### setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks) {#setRenderingPrintAreaAndPageBreaks-boolean-}
```
public void setRenderingPrintAreaAndPageBreaks(boolean renderingPrintAreaAndPageBreaks)
```


प्रिंट क्षेत्र के भीतर आने वाले पेज ब्रेक द्वारा वर्कशीट को रेंडर करने की सेटिंग करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderingPrintAreaAndPageBreaks | boolean | सक्षम करने के लिए true सेट करें, अक्षम करने के लिए false। |
|

### isRenderGridLines() {#isRenderGridLines--}
```
public final boolean isRenderGridLines()
```


ग्रिड लाइनों का रेंडरिंग सक्षम करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Returns:**
boolean -  true  यदि ग्रिड लाइन्स सक्षम हैं,  false  अन्यथा।

### setRenderGridLines(boolean value) {#setRenderGridLines-boolean-}
```
public final void setRenderGridLines(boolean value)
```


ग्रिड लाइनों के रेंडरिंग को सक्षम या अक्षम करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-worksheet-gridlines).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  ग्रिड लाइन्स रेंडरिंग सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### isSkipEmptyRows() {#isSkipEmptyRows--}
```
public final boolean isSkipEmptyRows()
```


रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं, यह दर्शाता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  यदि खाली पंक्तियों को छोड़ना चाहिए,  false  अन्यथा।

### setSkipEmptyRows(boolean value) {#setSkipEmptyRows-boolean-}
```
public final void setSkipEmptyRows(boolean value)
```


रेंडरिंग के दौरान खाली पंक्तियों को छोड़ना चाहिए या नहीं, यह सेट करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  खाली पंक्तियों को छोड़ने के लिए,  false  अन्यथा। |
|

### isSkipEmptyColumns() {#isSkipEmptyColumns--}
```
public final boolean isSkipEmptyColumns()
```


रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं, यह दर्शाता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Returns:**
boolean -  true  यदि खाली कॉलम छोड़े जाएँ,  false  अन्यथा।

### setSkipEmptyColumns(boolean value) {#setSkipEmptyColumns-boolean-}
```
public final void setSkipEmptyColumns(boolean value)
```


रेंडरिंग के दौरान खाली कॉलम को छोड़ना चाहिए या नहीं, यह सेट करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#skip-empty-rows-and-columns).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  खाली कॉलम को छोड़ने के लिए,  false  अन्यथा। |
|

### isRenderHiddenRows() {#isRenderHiddenRows--}
```
public final boolean isRenderHiddenRows()
```


निर्धारित करता है कि छिपी पंक्तियों को रेंडर किया जाना चाहिए या नहीं।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  यदि छिपी पंक्तियों को रेंडर किया जाना चाहिए,  false  अन्यथा।

### setRenderHiddenRows(boolean value) {#setRenderHiddenRows-boolean-}
```
public final void setRenderHiddenRows(boolean value)
```


छिपी पंक्तियों को रेंडर करना चाहिए या नहीं, यह सेट करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  छिपी पंक्तियों के रेंडरिंग को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### isRenderHeadings() {#isRenderHeadings--}
```
public boolean isRenderHeadings()
```


जाँचता है कि हेडिंग्स का रेंडरिंग सक्षम है या नहीं।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Returns:**
boolean -  true  यदि हेडिंग्स रेंडरिंग सक्षम है,  false  अन्यथा।

### setRenderHeadings(boolean renderHeadings) {#setRenderHeadings-boolean-}
```
public void setRenderHeadings(boolean renderHeadings)
```


हेडिंग्स का रेंडरिंग सक्षम करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-row-and-column-headings).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | renderHeadings | boolean | true  हेडिंग्स रेंडरिंग को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### isRenderHiddenColumns() {#isRenderHiddenColumns--}
```
public final boolean isRenderHiddenColumns()
```


छिपे कॉलम का रेंडरिंग सक्षम करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Returns:**
boolean -  true  यदि छिपे कॉलम रेंडरिंग सक्षम है,  false  अन्यथा।

### setRenderHiddenColumns(boolean value) {#setRenderHiddenColumns-boolean-}
```
public final void setRenderHiddenColumns(boolean value)
```


छिपे कॉलम का रेंडरिंग सक्षम करता है।


विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#render-hidden-rows-and-columns).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  छिपे कॉलम रेंडरिंग को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### getTextOverflowMode() {#getTextOverflowMode--}
```
public final TextOverflowMode getTextOverflowMode()
```


स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड लौटाता है।
विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Returns:**
[TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) - the text overflow mode.

### setTextOverflowMode(TextOverflowMode value) {#setTextOverflowMode-com.groupdocs.viewer.options.TextOverflowMode-}
```
public final void setTextOverflowMode(TextOverflowMode value)
```


स्प्रेडशीट दस्तावेज़ों को HTML में रेंडर करने के लिए टेक्स्ट ओवरफ़्लो मोड सेट करता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#control-cell-text-overflow).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [TextOverflowMode](../../com.groupdocs.viewer.options/textoverflowmode) | सेट किया जाने वाला टेक्स्ट ओवरफ़्लो मोड। |
|

### getLeftMargin() {#getLeftMargin--}
```
public double getLeftMargin()
```


PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है।


यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setLeftMargin(double leftMargin) {#setLeftMargin-double-}
```
public void setLeftMargin(double leftMargin)
```


PDF में परिवर्तित करते समय वर्कशीट का बायाँ मार्जिन सेट करने के लिए, यदि 0 से कम हो तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है।


यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| leftMargin | double |  |

### getRightMargin() {#getRightMargin--}
```
public double getRightMargin()
```


वर्कशीट के दाएँ मार्जिन को PDF में बदलते समय सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग होता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setRightMargin(double rightMargin) {#setRightMargin-double-}
```
public void setRightMargin(double rightMargin)
```


वर्कशीट के दाएँ मार्जिन को PDF में बदलते समय सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग होता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| rightMargin | double |  |

### getTopMargin() {#getTopMargin--}
```
public double getTopMargin()
```


वर्कशीट के शीर्ष मार्जिन को PDF में बदलते समय सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग होता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setTopMargin(double topMargin) {#setTopMargin-double-}
```
public void setTopMargin(double topMargin)
```


वर्कशीट के शीर्ष मार्जिन को PDF में बदलते समय सेट करने के लिए, यदि 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग होता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [दस्तावेज़ीकरण](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| topMargin | double |  |

### getBottomMargin() {#getBottomMargin--}
```
public double getBottomMargin()
```


वर्कशीट को PDF में परिवर्तित करते समय नीचे मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Returns:**
double
### setBottomMargin(double bottomMargin) {#setBottomMargin-double-}
```
public void setBottomMargin(double bottomMargin)
```


वर्कशीट को PDF में परिवर्तित करते समय नीचे मार्जिन सेट करने के लिए, यदि मान 0 से कम है तो डिफ़ॉल्ट रूपांतरण मान उपयोग किया जाता है। यदि पैरामीटर 0 से कम है, तो डिफ़ॉल्ट मान उपयोग किया जाता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-rendering-options/#set-worksheet-margins-in-the-output-pdf-pages).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| bottomMargin | double |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


जेनरेटेड इमेजों के लिए क्षैतिज रिज़ॉल्यूशन को डॉट्स प्रति इंच में प्राप्त करता है या सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Returns:**
int - DPI में क्षैतिज रिज़ॉल्यूशन।

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


जेनरेटेड इमेजों के लिए डॉट्स प्रति इंच में क्षैतिज रिज़ॉल्यूशन सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | horizontalResolution | int | DPI में क्षैतिज रिज़ॉल्यूशन। |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


जेनरेटेड इमेजों के लिए डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन प्राप्त करता है या सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Returns:**
int - DPI में लंबवत रिज़ॉल्यूशन।

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


जेनरेटेड इमेजों के लिए डॉट्स प्रति इंच में लंबवत रिज़ॉल्यूशन सेट करता है। यह विकल्प केवल स्प्रेडशीट को PNG या JPEG फ़ॉर्मेट में रेंडर करने पर उपयोग किया जाता है।


डिफ़ॉल्ट मान 96 DPI है। न्यूनतम संभव मान - 72 DPI, अधिकतम संभव मान - 600 DPI।
यदि उपयोगकर्ता द्वारा निर्दिष्ट मान इन सीमाओं से बाहर है, तो न्यूनतम या अधिकतम संभव मान लागू किया जाएगा।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | verticalResolution | int | DPI में लंबवत रिज़ॉल्यूशन। |
|

### forRenderingPrintAreaAndPageBreaks() {#forRenderingPrintAreaAndPageBreaks--}
```
public static SpreadsheetOptions forRenderingPrintAreaAndPageBreaks()
```


प्रिंट क्षेत्रों और पेज ब्रेक को रेंडर करने के लिए  SpreadsheetOptions  का एक नया इंस्टेंस इनिशियलाइज़ करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/#render-worksheet-by-page-breaks-and-print-area).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - New instance of  SpreadsheetOptions  for rendering pages based on page breaks that are included into print area. The behavior is similar to printing in Excel.

### forRenderingByPageBreaks() {#forRenderingByPageBreaks--}
```
public static SpreadsheetOptions forRenderingByPageBreaks()
```


केवल प्रिंट क्षेत्रों को रेंडर करने के लिए  SpreadsheetOptions  क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/split-worksheet-into-pages/).


**Returns:**
[SpreadsheetOptions](../../com.groupdocs.viewer.options/spreadsheetoptions) - a new instance of  SpreadsheetOptions  for rendering print areas only. The behavior is similar to printing in Excel, where the worksheet is rendered by page breaks.

