---
title: "TextOptions"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प।"
type: docs
weight: 32
url: /hi/nodejs-java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प।

TextOptions क्लास GroupDocs.Viewer कॉम्पोनेन्ट में टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प प्रदान करती है। यह आपको रेंडरिंग और व्यूइंग उद्देश्यों के लिए टेक्स्ट फ़ाइलों को व्यक्तिगत पृष्ठों में कैसे विभाजित किया जाए, इसे नियंत्रित करने की अनुमति देती है।

उदाहरण उपयोग:

```

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
```
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextOptions()](#TextOptions--) | TextOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getMaxCharsPerRow()](#getMaxCharsPerRow--) | पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या प्राप्त करता है। |
| [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या सेट करता है। |
| [getMaxRowsPerPage()](#getMaxRowsPerPage--) | पृष्ठ पर अधिकतम पंक्तियों की संख्या प्राप्त करता है। |
| [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | पृष्ठ पर अधिकतम पंक्तियों की संख्या सेट करता है। |
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


TextOptions क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

विवरण के लिए, देखें [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या प्राप्त करता है।

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या।
### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या सेट करता है।

***Note:** The default value is 85.* The default value is 85. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxCharsPerRow | int | पृष्ठ पर एक पंक्ति में अधिकतम अक्षरों की संख्या। |

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


पृष्ठ पर अधिकतम पंक्तियों की संख्या प्राप्त करता है।

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Returns:**
int - अधिकतम पंक्तियों की संख्या।
### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


पृष्ठ पर अधिकतम पंक्तियों की संख्या सेट करता है।

***Note:** The default value is 55.* The default value is 55. For details, see the [documentation][].


[documentation]: https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| maxRowsPerPage | int | अधिकतम पंक्तियों की संख्या। |

