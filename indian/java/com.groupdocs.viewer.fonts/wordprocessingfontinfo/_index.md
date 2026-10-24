---
title: "WordProcessingFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer इंस्टेंस में लोड किए गए WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है।"
type: docs
weight: 17
url: /hi/java/com.groupdocs.viewer.fonts/wordprocessingfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingFontInfo implements IFontInfo
```

Viewer इंस्टेंस में लोड किए गए WordProcessing दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग होता है और दस्तावेज़ के भीतर एम्बेड किया गया है या उस ऑपरेटिंग सिस्टम में स्थापित है जहाँ GroupDocs.Viewer चल रहा है।

अपरिवर्तनीय क्लास। इसके इंस्टेंस GroupDocs.Viewer द्वारा निर्मित और लौटाए जाते हैं।
सार्वजनिक API और सामान्यतः उपयोगकर्ता द्वारा नहीं बनाया जाना चाहिए।
विवरण के लिए, दस्तावेज़ देखें:
https://docs.groupdocs.com/viewer/net/getting-used-fonts/

## Methods

| Method | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | फ़ॉन्ट का फ़ैमिली नाम, बिना शैली के, कभी भी null या खाली नहीं। |
|
|  | [getAltFamilyName()](#getAltFamilyName--) | फ़ॉन्ट का वैकल्पिक फ़ैमिली नाम। |
|
|  | [getStyle()](#getStyle--) | फ़ॉन्ट की शैली — Regular, Bold, Italic, या BoldItalic हो सकती है। |
|
|  | [isEmbedded()](#isEmbedded--) | यह दर्शाता है कि यह फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है (true) या सिस्टम फ़ॉन्ट है (false)। |
|
|  | [getFormat()](#getFormat--) | इस फ़ॉन्ट का फ़ॉर्मेट। |
|
|  | [getContent()](#getContent--) | फ़ॉन्ट की सामग्री बाइट एरे के रूप में, या यदि उपलब्ध नहीं है तो null। |
|
|  | [getCharset()](#getCharset--) | इस फ़ॉन्ट का कैरेक्टर सेट। |
|
|  | [toString()](#toString--) | निम्न टेम्पलेट में इस फ़ॉन्ट के बारे में डिबग जानकारी लौटाता है: "name style, embedded/system, format" |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | इस फ़ॉन्ट जानकारी को @font-face CSS नियम के रूप में सीरियलाइज़ करता है और इसे निर्दिष्ट राइटर में लिखता है। |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट का फ़ैमिली नाम, बिना शैली के, कभी भी null या खाली नहीं।


**Returns:**
java.lang.String
### getAltFamilyName() {#getAltFamilyName--}
```
public String getAltFamilyName()
```


फ़ॉन्ट का वैकल्पिक फ़ैमिली नाम। यदि अनुपलब्ध है, तो खाली स्ट्रिंग लौटाता है।


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


फ़ॉन्ट की शैली — Regular, Bold, Italic, या BoldItalic हो सकती है।


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


यह दर्शाता है कि यह फ़ॉन्ट दस्तावेज़ के भीतर एम्बेडेड है (true) या सिस्टम फ़ॉन्ट है (false)।


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


इस फ़ॉन्ट का फ़ॉर्मेट। यदि केवल मेटा जानकारी है और बाइनरी सामग्री अनुपलब्ध है, तो FontFormat.UNKNOWN लौटाया जा सकता है।


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


फ़ॉन्ट की सामग्री बाइट एरे के रूप में, या यदि उपलब्ध नहीं है तो null।


**Returns:**
byte[]
### getCharset() {#getCharset--}
```
public int getCharset()
```


इस फ़ॉन्ट का कैरेक्टर सेट।


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


निम्न टेम्पलेट में इस फ़ॉन्ट के बारे में डिबग जानकारी लौटाता है: "name style, embedded/system, format"


**Returns:**
java.lang.String
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


इस फ़ॉन्ट जानकारी को @font-face CSS नियम के रूप में सीरियलाइज़ करता है और इसे निर्दिष्ट राइटर में लिखता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | output | java.io.Writer | सीरियलाइज़्ड CSS प्राप्त करने के लिए राइटर। |
|

