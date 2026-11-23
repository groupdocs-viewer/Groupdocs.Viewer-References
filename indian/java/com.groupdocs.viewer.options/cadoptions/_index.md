---
title: "CadOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "CAD ड्रॉइंग्स को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD ड्रॉइंग्स को रेंडर करने के विकल्प प्रदान करता है।


CadOptions क्लास विभिन्न सेटिंग्स और पैरामीटरों को समाहित करती है जिन्हें उपयोग किया जा सकता है
GroupDocs.Viewer घटक में CAD ड्रॉइंग्स के रेंडरिंग को नियंत्रित करने के लिए।


अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render CAD drawings and models as HTML, PDF, and image files](../https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/) और [Specify rendering options for CAD files](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/).


उदाहरण उपयोग:

````

 CadOptions options = CadOptions.forRenderingByWidth(256);
 options.setRenderLayouts(true);
 options.setBackgroundColor(Color.YELLOW);
 options.setLayers(Arrays.asList(
         CacheableFactory.getInstance().newLayer("Layer1"),
         CacheableFactory.getInstance().newLayer("Layer2")
 ));

 try (Viewer viewer = new Viewer("document.dwg")) {
     PdfViewOptions pdfViewOptions = new PdfViewOptions();
     pdfViewOptions.setCadOptions(options);
     viewer.view(pdfViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Fields

| Field | विवरण |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [getPc3File()](#getPc3File--) | प्लॉटर से संबंधित PC3 (Plotter Configuration) फ़ाइल को पुनः प्राप्त करता है। |
|
|  | [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | प्लॉटर से संबंधित PC3 (Plotter Configuration) फ़ाइल को सेट करता है। |
|
|  | [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | नए उदाहरण को प्रारंभ करता है |
CadOptions
स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए क्लास।
|
|  | [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | नए उदाहरण को प्रारंभ करता है |
CadOptions
चौड़ाई द्वारा रेंडरिंग के लिए क्लास।
|
|  | [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | नए उदाहरण को प्रारंभ करता है |
CadOptions
ऊँचाई द्वारा रेंडरिंग के लिए क्लास।
|
|  | [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | नए उदाहरण को प्रारंभ करता है |
CadOptions
चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए क्लास।
|
|  | [getScaleFactor()](#getScaleFactor--) | रेंडरिंग के लिए स्केल फ़ैक्टर प्राप्त करता है। |
|
|  | [getWidth()](#getWidth--) | आउटपुट परिणाम की चौड़ाई पिक्सेल में प्राप्त करता है। |
|
|  | [getHeight()](#getHeight--) | आउटपुट परिणाम की ऊँचाई पिक्सेल में प्राप्त करता है। |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | छवि का पृष्ठभूमि रंग प्राप्त करता है। |
|
|  | [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | छवि का पृष्ठभूमि रंग प्राप्त करता है। |
|
|  | [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | छवि का पृष्ठभूमि रंग सेट करता है। |
|
|  | [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | छवि का पृष्ठभूमि रंग सेट करता है। |
|
|  | [getTiles()](#getTiles--) | रेंडर करने के लिए ड्राइंग क्षेत्रों को प्राप्त करता है। |
|
|  | [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | रेंडर करने के लिए ड्राइंग क्षेत्रों को सेट करता है। |
|
|  | [isRenderLayouts()](#isRenderLayouts--) | निर्देशित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं। |
|
|  | [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | निर्धारित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं। |
|
|  | [getLayoutName()](#getLayoutName--) | रेंडर करने के लिए विशिष्ट लेआउट का नाम प्राप्त करता है। |
|
|  | [setLayoutName(String value)](#setLayoutName-java.lang.String-) | रेंडर करने के लिए विशिष्ट लेआउट का नाम सेट करता है। |
|
|  | [getLayers()](#getLayers--) | रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है। |
|
|  | [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है। |
|
|  | [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मेट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम हो जाता है। |
|
|  | [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मेट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम हो जाता है। |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | जाँचता है कि यह CadOptions ऑब्जेक्ट किसी अन्य ऑब्जेक्ट के बराबर है या नहीं। |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
|  | [toString()](#toString--) | {@inheritDoc} |
|
|  | [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | {@inheritDoc} |
|
### WIDTH {#WIDTH}
```
public static final String WIDTH
```


### HEIGHT {#HEIGHT}
```
public static final String HEIGHT
```


### getPc3File() {#getPc3File--}
```
public String getPc3File()
```


प्लॉटर से संबंधित PC3 (Plotter Configuration) फ़ाइल को पुनः प्राप्त करता है।


**Returns:**
java.lang.String - PC3 फ़ाइल पथ।

### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


प्लॉटर से संबंधित PC3 (Plotter Configuration) फ़ाइल को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | pc3File | java.lang.String | PC3 फ़ाइल पथ। |
|

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


नए उदाहरण को प्रारंभ करता है
CadOptions
स्केल फ़ैक्टर द्वारा रेंडरिंग के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | scaleFactor | double | रेंडरिंग के लिए स्केल फ़ैक्टर। 1 से बड़े मान आउटपुट परिणाम को बड़ा करेंगे, जबकि 0 और 1 के बीच के मान आउटपुट परिणाम को छोटा करेंगे। |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.

### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


नए उदाहरण को प्रारंभ करता है
CadOptions
चौड़ाई द्वारा रेंडरिंग के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | width | int | आउटपुट परिणाम की चौड़ाई पिक्सेल में। |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.

### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


नए उदाहरण को प्रारंभ करता है
CadOptions
ऊँचाई द्वारा रेंडरिंग के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | ऊँचाई | int | आउटपुट परिणाम की ऊँचाई पिक्सेल में। |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.

### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


नए उदाहरण को प्रारंभ करता है
CadOptions
चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए क्लास।


कोड उदाहरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size).


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | width | int | आउटपुट परिणाम की चौड़ाई पिक्सेल में। |
|
|  | ऊँचाई | int | आउटपुट परिणाम की ऊँचाई पिक्सेल में। |
|

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.

### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


रेंडरिंग के लिए स्केल फ़ैक्टर प्राप्त करता है।
1 से बड़े मान आउटपुट परिणाम को बड़ा करेंगे, जबकि 0 और 1 के बीच के मान इसे छोटा करेंगे।


**Returns:**
double - रेंडरिंग के लिए स्केल फ़ैक्टर।

### getWidth() {#getWidth--}
```
public final int getWidth()
```


आउटपुट परिणाम की चौड़ाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - आउटपुट परिणाम की चौड़ाई।

### getHeight() {#getHeight--}
```
public final int getHeight()
```


आउटपुट परिणाम की ऊँचाई पिक्सेल में प्राप्त करता है।


**Returns:**
int - आउटपुट परिणाम की ऊँचाई।

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


छवि का पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
java.awt.Color - छवि की पृष्ठभूमि का रंग।

### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


छवि का पृष्ठभूमि रंग प्राप्त करता है।


**Returns:**
java.lang.String - 0xFFFFFF प्रारूप में छवि की पृष्ठभूमि का रंग।

### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


छवि का पृष्ठभूमि रंग सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | backgroundColor | java.awt.Color | छवि की पृष्ठभूमि का रंग। |
|

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


छवि का पृष्ठभूमि रंग सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | colorName | java.lang.String | छवि की पृष्ठभूमि रंग का नाम। |
|

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


रेंडर करने के लिए ड्राइंग क्षेत्रों को प्राप्त करता है।
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
यह
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
और
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) विकल्पों को अनदेखा किया जाता है
टाइल्स द्वारा रेंडरिंग करते समय.*


**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - रेंडर करने के लिए ड्राइंग क्षेत्रों की सूची।

### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


रेंडर करने के लिए ड्राइंग क्षेत्रों को सेट करता है।
***Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT) file types.
यह
RenderLayouts
([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoperations#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoperations#setRenderLayouts-boolean-))
और
LayoutName
([getLayoutName()](../../com.groupdocs.viewer.options/cadoperations#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoperations#setLayoutName-String-)) विकल्पों को अनदेखा किया जाता है
टाइल्स द्वारा रेंडरिंग करते समय.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<com.groupdocs.viewer.options.Tile> | रेंडर करने के लिए ड्राइंग क्षेत्रों की सूची। |
|

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


निर्देशित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं।
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
डिफ़ॉल्ट रूप से, केवल मॉडल रेंडर किया जाता है।*


**Returns:**
boolean -  true  यदि लेआउट्स को रेंडर किया जाना चाहिए,  false  अन्यथा।

### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


निर्धारित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं।
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
डिफ़ॉल्ट रूप से, केवल मॉडल रेंडर किया जाता है।*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | boolean | true  लेआउट्स को रेंडर करने के लिए,  false  अन्यथा। |
|

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


विशिष्ट लेआउट को रेंडर करने के लिए उसका नाम प्राप्त करता है। लेआउट नाम केस-सेंसिटिव है।
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
डिफ़ॉल्ट रूप से, केवल मॉडल रेंडर किया जाता है।*


**Returns:**
java.lang.String - विशिष्ट लेआउट को रेंडर करने के लिए उसका नाम।

### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


विशिष्ट लेआउट को रेंडर करने के लिए उसका नाम सेट करता है। लेआउट नाम केस-सेंसिटिव है।
***Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype#DWFX).
डिफ़ॉल्ट रूप से, केवल मॉडल रेंडर किया जाता है।*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.lang.String | विशिष्ट लेआउट को रेंडर करने के लिए उसका नाम। |
|

### getLayers() {#getLayers--}
```
public final List<Layer> getLayers()
```


रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है।


**Note:** By default, all layers are rendered. Layer names are case-sensitive.


**Returns:**
java.util.List<com.groupdocs.viewer.results.Layer> - CAD ड्राइंग लेयर्स।

### setLayers(List<Layer> value) {#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--}
```
public final void setLayers(List<Layer> value)
```


रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है।
***Note:** By default, all layers are rendered. Layer names are case-sensitive.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | मान | java.util.List<com.groupdocs.viewer.results.Layer> | CAD ड्राइंग लेयर। |
|

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम हो जाता है। इस मोड में, रूपांतरण गति बहुत तेज़ होती है, लेकिन परिणामी दस्तावेज़ों की गुणवत्ता काफी घट जाती है। डिफ़ॉल्ट रूप से, यह निष्क्रिय (false) रहता है। प्रदर्शन की कीमत पर परिणामी दस्तावेज़ों की गुणवत्ता संभवतः सर्वोत्तम होती है।


**Returns:**
boolean -  true  यदि प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम है,  false  अन्यथा।

### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम हो जाता है। इस मोड में, रूपांतरण गति बहुत तेज़ होती है, लेकिन परिणामी दस्तावेज़ों की गुणवत्ता काफी घट जाती है। डिफ़ॉल्ट रूप से, यह निष्क्रिय (false) रहता है। प्रदर्शन की कीमत पर परिणामी दस्तावेज़ों की गुणवत्ता संभवतः सर्वोत्तम होती है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | enablePerformanceConversionMode | boolean | true  प्रदर्शन-उन्मुख रूपांतरण मोड को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


जाँचता है कि यह CadOptions ऑब्जेक्ट किसी अन्य ऑब्जेक्ट के बराबर है या नहीं।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | o | java.lang.Object | तुलना करने के लिए वस्तु। |
|

**Returns:**
boolean -  true  यदि वस्तुएँ समान हैं,  false  अन्यथा।

### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड आधारित है
वस्तु की आंतरिक स्थिति पर और हैश-आधारित डेटा संरचनाओं में उपयोग किया जाता है
जैसे हैश मैप और हैश सेट।
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - इस वस्तु के लिए हैश कोड मान।

### toString() {#toString--}
```
public String toString()
```


इस वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है।
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Returns:**
java.lang.String - इस वस्तु का स्ट्रिंग प्रतिनिधित्व।

### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


इस वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है।
***Note:** This method overrides the default implementation of the toString() method defined in the Object class.*


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्टाइल | org.apache.commons.lang3.builder.ToStringStyle | स्ट्रिंग प्रतिनिधित्व उत्पन्न करने के लिए उपयोग करने वाला ToStringStyle। |
|

**Returns:**
java.lang.String - निर्दिष्ट ToStringStyle का उपयोग करके इस वस्तु का स्ट्रिंग प्रतिनिधित्व।

