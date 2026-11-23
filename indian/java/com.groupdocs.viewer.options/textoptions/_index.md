---
title: "TextOptions"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प।"
type: docs
weight: 32
url: /hi/java/com.groupdocs.viewer.options/textoptions/
---
**Inheritance:**
java.lang.Object
```
public class TextOptions
```

टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प।


TextOptions क्लास GroupDocs.Viewer घटक में टेक्स्ट फ़ाइलों को पृष्ठों में विभाजित करने के विकल्प प्रदान करती है।
यह आपको रेंडरिंग और व्यूइंग उद्देश्यों के लिए टेक्स्ट फ़ाइलों को व्यक्तिगत पृष्ठों में कैसे विभाजित किया जाता है, नियंत्रित करने की सुविधा देता है।


उदाहरण उपयोग:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 TextOptions options = pngViewOptions.getTextOptions();
 options.setMaxCharsPerRow(96);
 options.setMaxRowsPerPage(48);

 try (Viewer viewer = new Viewer("document.txt")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [TextOptions()](#TextOptions--) | नए उदाहरण को प्रारंभ करता है |
TextOptions
class।
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getMaxCharsPerRow()](#getMaxCharsPerRow--) | पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या प्राप्त करता है। |
|
|  | [setMaxCharsPerRow(int maxCharsPerRow)](#setMaxCharsPerRow-int-) | पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या सेट करता है। |
|
|  | [getMaxRowsPerPage()](#getMaxRowsPerPage--) | पृष्ठ पर अधिकतम पंक्तियों की संख्या प्राप्त करता है। |
|
|  | [setMaxRowsPerPage(int maxRowsPerPage)](#setMaxRowsPerPage-int-) | पृष्ठ पर अधिकतम पंक्तियों की संख्या सेट करता है। |
|
### TextOptions() {#TextOptions--}
```
public TextOptions()
```


नए उदाहरण को प्रारंभ करता है
TextOptions
class।
विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options)।


### getMaxCharsPerRow() {#getMaxCharsPerRow--}
```
public int getMaxCharsPerRow()
```


पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या प्राप्त करता है।


***Note:** The default value is 85.*
डिफ़ॉल्ट मान 85 है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options)।


**Returns:**
int - पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या।

### setMaxCharsPerRow(int maxCharsPerRow) {#setMaxCharsPerRow-int-}
```
public void setMaxCharsPerRow(int maxCharsPerRow)
```


पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या सेट करता है।


***Note:** The default value is 85.*
डिफ़ॉल्ट मान 85 है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxCharsPerRow | int | पृष्ठ पर प्रति पंक्ति अधिकतम अक्षरों की संख्या। |
|

### getMaxRowsPerPage() {#getMaxRowsPerPage--}
```
public int getMaxRowsPerPage()
```


पृष्ठ पर अधिकतम पंक्तियों की संख्या प्राप्त करता है।


***Note:** The default value is 55.*
डिफ़ॉल्ट मान 55 है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options)।


**Returns:**
int - अधिकतम पंक्तियों की संख्या।

### setMaxRowsPerPage(int maxRowsPerPage) {#setMaxRowsPerPage-int-}
```
public void setMaxRowsPerPage(int maxRowsPerPage)
```


पृष्ठ पर अधिकतम पंक्तियों की संख्या सेट करता है।


***Note:** The default value is 55.*
डिफ़ॉल्ट मान 55 है। विवरण के लिए, देखें [documentation](../https://docs.groupdocs.com/viewer/java/render-text-files/#specify-rendering-options)।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | maxRowsPerPage | int | अधिकतम पंक्तियों की संख्या। |
|

