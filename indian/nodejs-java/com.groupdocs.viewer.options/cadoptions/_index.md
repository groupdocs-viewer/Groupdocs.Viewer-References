---
title: "CadOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "CAD ड्रॉइंग्स को रेंडर करने के विकल्प प्रदान करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.viewer.options/cadoptions/
---
**Inheritance:**
java.lang.Object
```
public class CadOptions
```

CAD ड्रॉइंग्स को रेंडर करने के विकल्प प्रदान करता है।

CadOptions क्लास विभिन्न सेटिंग्स और पैरामीटर को समाहित करती है जिन्हें GroupDocs.Viewer घटक में CAD ड्रॉइंग्स के रेंडरिंग को नियंत्रित करने के लिए उपयोग किया जा सकता है।

अधिक जानकारी और कोड उदाहरणों के लिए, देखें [Render CAD drawings and models as HTML, PDF, and image files][Render CAD drawings and models as HTML_ PDF_ and image files] और [Specify rendering options for CAD files][].

उदाहरण उपयोग:

```

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
 
```


[Render CAD drawings and models as HTML_ PDF_ and image files]: https://docs.groupdocs.com/viewer/java/render-cad-drawings-and-models/
[Specify rendering options for CAD files]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [WIDTH](#WIDTH) |  |
| [HEIGHT](#HEIGHT) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPc3File()](#getPc3File--) | प्लॉटर से जुड़ी PC3 (Plotter Configuration) फ़ाइल प्राप्त करता है। |
| [setPc3File(String pc3File)](#setPc3File-java.lang.String-) | प्लॉटर से जुड़ी PC3 (Plotter Configuration) फ़ाइल सेट करता है। |
| [forRenderingByScaleFactor(double scaleFactor)](#forRenderingByScaleFactor-double-) | स्केल फैक्टर द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forRenderingByWidth(int width)](#forRenderingByWidth-int-) | चौड़ाई द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forRenderingByHeight(int height)](#forRenderingByHeight-int-) | ऊँचाई द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [forRenderingByWidthAndHeight(int width, int height)](#forRenderingByWidthAndHeight-int-int-) | चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए CadOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
| [getScaleFactor()](#getScaleFactor--) | रेंडरिंग के लिए स्केल फ़ैक्टर प्राप्त करता है। |
| [getWidth()](#getWidth--) | आउटपुट परिणाम की चौड़ाई पिक्सेल में प्राप्त करता है। |
| [getHeight()](#getHeight--) | आउटपुट परिणाम की ऊँचाई पिक्सेल में प्राप्त करता है। |
| [getBackgroundColor()](#getBackgroundColor--) | छवि का बैकग्राउंड रंग प्राप्त करता है। |
| [getBackgroundColorAsHex()](#getBackgroundColorAsHex--) | छवि का बैकग्राउंड रंग प्राप्त करता है। |
| [setBackgroundColor(Color backgroundColor)](#setBackgroundColor-java.awt.Color-) | छवि का बैकग्राउंड रंग सेट करता है। |
| [setBackgroundColor(String colorName)](#setBackgroundColor-java.lang.String-) | छवि का बैकग्राउंड रंग सेट करता है। |
| [getTiles()](#getTiles--) | रेंडर करने के लिए ड्राइंग क्षेत्रों को प्राप्त करता है। |
| [setTiles(List<Tile> value)](#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--) | रेंडर करने के लिए ड्राइंग क्षेत्रों को सेट करता है। |
| [isRenderLayouts()](#isRenderLayouts--) | निर्देशित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं। |
| [setRenderLayouts(boolean value)](#setRenderLayouts-boolean-) | सेट करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं। |
| [getLayoutName()](#getLayoutName--) | रेंडर करने के लिए विशिष्ट लेआउट का नाम प्राप्त करता है। |
| [setLayoutName(String value)](#setLayoutName-java.lang.String-) | रेंडर करने के लिए विशिष्ट लेआउट का नाम सेट करता है। |
| [getLayers()](#getLayers--) | रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है। |
| [setLayers(List<Layer> value)](#setLayers-java.util.List-com.groupdocs.viewer.results.Layer--) | रेंडर करने के लिए CAD ड्राइंग लेयर्स को प्राप्त करता है। |
| [isEnablePerformanceConversionMode()](#isEnablePerformanceConversionMode--) | इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम होता है। |
| [setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)](#setEnablePerformanceConversionMode-boolean-) | इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम होता है। |
| [equals(Object o)](#equals-java.lang.Object-) | जाँचता है कि यह CadOptions ऑब्जेक्ट किसी अन्य ऑब्जेक्ट के बराबर है या नहीं। |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | \{@inheritDoc\} |
| [toString(ToStringStyle style)](#toString-org.apache.commons.lang3.builder.ToStringStyle-) | \{@inheritDoc\} |
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


प्लॉटर से जुड़ी PC3 (Plotter Configuration) फ़ाइल प्राप्त करता है।

**Returns:**
java.lang.String - PC3 फ़ाइल पथ।
### setPc3File(String pc3File) {#setPc3File-java.lang.String-}
```
public void setPc3File(String pc3File)
```


प्लॉटर से जुड़ी PC3 (Plotter Configuration) फ़ाइल सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pc3File | java.lang.String | PC3 फ़ाइल पथ। |

### forRenderingByScaleFactor(double scaleFactor) {#forRenderingByScaleFactor-double-}
```
public static CadOptions forRenderingByScaleFactor(double scaleFactor)
```


स्केल फैक्टर द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| scaleFactor | double | रेंडरिंग के लिए स्केल फ़ैक्टर। 1 से बड़े मान आउटपुट परिणाम को बड़ा करेंगे, जबकि 0 और 1 के बीच के मान आउटपुट परिणाम को छोटा करेंगे। |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by scale factor.
### forRenderingByWidth(int width) {#forRenderingByWidth-int-}
```
public static CadOptions forRenderingByWidth(int width)
```


चौड़ाई द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | आउटपुट परिणाम की चौड़ाई पिक्सेल में। |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width.
### forRenderingByHeight(int height) {#forRenderingByHeight-int-}
```
public static CadOptions forRenderingByHeight(int height)
```


ऊँचाई द्वारा रेंडरिंग के लिए CadOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| height | int | आउटपुट परिणाम की ऊँचाई पिक्सेल में। |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by height.
### forRenderingByWidthAndHeight(int width, int height) {#forRenderingByWidthAndHeight-int-int-}
```
public static CadOptions forRenderingByWidthAndHeight(int width, int height)
```


चौड़ाई और ऊँचाई द्वारा रेंडरिंग के लिए CadOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

कोड उदाहरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/specify-cad-rendering-options/#configure-the-output-image-size

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| width | int | आउटपुट परिणाम की चौड़ाई पिक्सेल में। |
| height | int | आउटपुट परिणाम की ऊँचाई पिक्सेल में। |

**Returns:**
[CadOptions](../../com.groupdocs.viewer.options/cadoptions) - a new instance of the  CadOptions  class for rendering by width and height.
### getScaleFactor() {#getScaleFactor--}
```
public final double getScaleFactor()
```


रेंडरिंग के लिए स्केल फ़ैक्टर प्राप्त करता है। 1 से बड़े मान आउटपुट परिणाम को बड़ा करेंगे, जबकि 0 और 1 के बीच के मान आउटपुट परिणाम को छोटा करेंगे।

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


छवि का बैकग्राउंड रंग प्राप्त करता है।

**Returns:**
java.awt.Color - छवि की पृष्ठभूमि का रंग।
### getBackgroundColorAsHex() {#getBackgroundColorAsHex--}
```
public String getBackgroundColorAsHex()
```


छवि का बैकग्राउंड रंग प्राप्त करता है।

**Returns:**
java.lang.String - 0xFFFFFF प्रारूप में छवि की पृष्ठभूमि का रंग।
### setBackgroundColor(Color backgroundColor) {#setBackgroundColor-java.awt.Color-}
```
public void setBackgroundColor(Color backgroundColor)
```


छवि का बैकग्राउंड रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| backgroundColor | java.awt.Color | छवि की पृष्ठभूमि का रंग। |

### setBackgroundColor(String colorName) {#setBackgroundColor-java.lang.String-}
```
public void setBackgroundColor(String colorName)
```


छवि का बैकग्राउंड रंग सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| colorName | java.lang.String | छवि की पृष्ठभूमि रंग का नाम। |

### getTiles() {#getTiles--}
```
public final List<Tile> getTiles()
```


रेंडर करने के लिए ड्राइंग क्षेत्रों को प्राप्त करता है।

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Returns:**
java.util.List<com.groupdocs.viewer.options.Tile> - रेंडर करने के लिए ड्राइंग क्षेत्रों की सूची।
### setTiles(List<Tile> value) {#setTiles-java.util.List-com.groupdocs.viewer.options.Tile--}
```
public final void setTiles(List<Tile> value)
```


रेंडर करने के लिए ड्राइंग क्षेत्रों को सेट करता है।

**Note:** This option is supported only for [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG) and [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT) file types. The  RenderLayouts  ([isRenderLayouts()](../../com.groupdocs.viewer.options/cadoptions\#isRenderLayouts--)/[setRenderLayouts(boolean)](../../com.groupdocs.viewer.options/cadoptions\#setRenderLayouts-boolean-)) and  LayoutName  ([getLayoutName()](../../com.groupdocs.viewer.options/cadoptions\#getLayoutName--)/[setLayoutName(String)](../../com.groupdocs.viewer.options/cadoptions\#setLayoutName-String-)) options are ignored when rendering by tiles.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.options.Tile> | रेंडर करने के लिए ड्राइंग क्षेत्रों की सूची। |

### isRenderLayouts() {#isRenderLayouts--}
```
public final boolean isRenderLayouts()
```


निर्देशित करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं।

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
boolean -  true  यदि लेआउट रेंडर किए जाने चाहिए,  false  अन्यथा।
### setRenderLayouts(boolean value) {#setRenderLayouts-boolean-}
```
public final void setRenderLayouts(boolean value)
```


सेट करता है कि CAD दस्तावेज़ से लेआउट रेंडर किए जाने चाहिए या नहीं।

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean | true  लेआउट रेंडर करने के लिए,  false  अन्यथा। |

### getLayoutName() {#getLayoutName--}
```
public final String getLayoutName()
```


विशिष्ट लेआउट को रेंडर करने के लिए नाम प्राप्त करता है। लेआउट नाम केस-सेंसिटिव है।

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Returns:**
java.lang.String - विशिष्ट लेआउट को रेंडर करने के लिए नाम।
### setLayoutName(String value) {#setLayoutName-java.lang.String-}
```
public final void setLayoutName(String value)
```


विशिष्ट लेआउट को रेंडर करने के लिए नाम सेट करता है। लेआउट नाम केस-सेंसिटिव है।

**Note:** This option applies only to CAD drawings that support layouts, such as [FileType.DXF](../../com.groupdocs.viewer/filetype\#DXF), [FileType.DWG](../../com.groupdocs.viewer/filetype\#DWG), [FileType.DWT](../../com.groupdocs.viewer/filetype\#DWT), [FileType.DWF](../../com.groupdocs.viewer/filetype\#DWF), and [FileType.DWFX](../../com.groupdocs.viewer/filetype\#DWFX). By default, only the Model is rendered.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String | विशिष्ट लेआउट को रेंडर करने के लिए नाम। |

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

**Note:** By default, all layers are rendered. Layer names are case-sensitive.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.viewer.results.Layer> | CAD ड्राइंग लेयर्स। |

### isEnablePerformanceConversionMode() {#isEnablePerformanceConversionMode--}
```
public boolean isEnablePerformanceConversionMode()
```


इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम होता है। इस मोड में रूपांतरण गति बहुत तेज़ होती है, लेकिन परिणामी दस्तावेज़ों की गुणवत्ता काफी घट जाती है। डिफ़ॉल्ट रूप से, यह निष्क्रिय (false) रहता है। प्रदर्शन की कीमत पर परिणामी दस्तावेज़ों की गुणवत्ता संभवतः सर्वोत्तम होती है।

**Returns:**
boolean -  true  यदि प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम है,  false  अन्यथा।
### setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode) {#setEnablePerformanceConversionMode-boolean-}
```
public void setEnablePerformanceConversionMode(boolean enablePerformanceConversionMode)
```


इस फ़्लैग को true सेट करने से CAD परिवार के सभी फ़ॉर्मैट्स के लिए एक विशेष प्रदर्शन-उन्मुख रूपांतरण मोड सक्षम होता है। इस मोड में रूपांतरण गति बहुत तेज़ होती है, लेकिन परिणामी दस्तावेज़ों की गुणवत्ता काफी घट जाती है। डिफ़ॉल्ट रूप से, यह निष्क्रिय (false) रहता है। प्रदर्शन की कीमत पर परिणामी दस्तावेज़ों की गुणवत्ता संभवतः सर्वोत्तम होती है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| enablePerformanceConversionMode | boolean | true  प्रदर्शन-उन्मुख रूपांतरण मोड को सक्षम करने के लिए,  false  इसे निष्क्रिय करने के लिए। |

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


जाँचता है कि यह CadOptions ऑब्जेक्ट किसी अन्य ऑब्जेक्ट के बराबर है या नहीं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| o | java.lang.Object | तुलना करने के लिए वस्तु। |

**Returns:**
boolean -  true  यदि वस्तुएँ समान हैं,  false  अन्यथा।
### hashCode() {#hashCode--}
```
public int hashCode()
```


इस वस्तु के लिए हैश कोड मान की गणना करता है। हैश कोड वस्तु की आंतरिक स्थिति पर आधारित होता है और हैश-आधारित डेटा संरचनाओं जैसे हैश मैप और हैश सेट में उपयोग किया जाता है।

**Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.

**Returns:**
int - इस वस्तु के लिए हैश कोड मान।
### toString() {#toString--}
```
public String toString()
```


इस वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Returns:**
java.lang.String - इस वस्तु का स्ट्रिंग प्रतिनिधित्व।
### toString(ToStringStyle style) {#toString-org.apache.commons.lang3.builder.ToStringStyle-}
```
public String toString(ToStringStyle style)
```


इस वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है।

**Note:** This method overrides the default implementation of the toString() method defined in the Object class.

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शैली | org.apache.commons.lang3.builder.ToStringStyle | स्ट्रिंग प्रतिनिधित्व उत्पन्न करने के लिए उपयोग किया जाने वाला ToStringStyle। |

**Returns:**
java.lang.String - निर्दिष्ट ToStringStyle का उपयोग करके इस वस्तु का स्ट्रिंग प्रतिनिधित्व।
