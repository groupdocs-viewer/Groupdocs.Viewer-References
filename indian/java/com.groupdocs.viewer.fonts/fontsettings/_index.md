---
title: "FontSettings"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "TrueType फ़ॉन्ट्स खोजने के लिए स्रोतों के साथ काम करने की विधियाँ प्रदान करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.viewer.fonts/fontsettings/
---
**Inheritance:**
java.lang.Object
```
public class FontSettings
```

TrueType फ़ॉन्ट्स खोजने के लिए स्रोतों के साथ काम करने की विधियाँ प्रदान करता है।


FontSettings क्लास का उपयोग TrueType फ़ॉन्ट्स को खोजने के लिए स्रोतों को निर्दिष्ट करने और प्रबंधित करने के लिए किया जाता है।
यह GroupDocs.Viewer API के लिए फ़ॉन्ट स्रोतों को जोड़ने और रीसेट करने के लिए विधियाँ प्रदान करता है।


उदाहरण उपयोग:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Constructors

| Constructor | विवरण |
| --- | --- |
| [FontSettings()](#FontSettings--) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [setFontSources(FontSource[] fontSources)](#setFontSources-com.groupdocs.viewer.fonts.FontSource...-) | दस्तावेज़ रेंडर करते समय TrueType फ़ॉन्ट्स को खोजने के लिए स्रोतों को सेट करता है। |
|
|  | [resetFontSources()](#resetFontSources--) | पहले सेट किए गए फ़ॉन्ट स्रोतों को रीसेट करता है। |
|
### FontSettings() {#FontSettings--}
```
public FontSettings()
```


### setFontSources(FontSource[] fontSources) {#setFontSources-com.groupdocs.viewer.fonts.FontSource...-}
```
public static void setFontSources(FontSource[] fontSources)
```


दस्तावेज़ रेंडर करते समय TrueType फ़ॉन्ट्स को खोजने के लिए स्रोतों को सेट करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | fontSources | [FontSource\[\]](../../com.groupdocs.viewer.fonts/fontsource) | सेट करने के लिए फ़ॉन्ट स्रोत। |
|

### resetFontSources() {#resetFontSources--}
```
public static void resetFontSources()
```


पहले सेट किए गए फ़ॉन्ट स्रोतों को रीसेट करता है।


