---
title: "PresentationFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer इंस्टेंस में लोड किए गए Presentation दस्तावेज़ में उपयोग किए गए फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को संलग्न करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.viewer.fonts/presentationfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class PresentationFontInfo implements IFontInfo
```

Viewer इंस्टेंस में लोड किए गए Presentation दस्तावेज़ में उपयोग किए गए फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को संलग्न करता है। यह फ़ॉन्ट दस्तावेज़ की सामग्री में उपयोग होता है और दस्तावेज़ के भीतर एम्बेडेड हो सकता है या उस ऑपरेटिंग सिस्टम में स्थापित हो सकता है जहाँ GroupDocs.Viewer चल रहा है।

## Methods

| Method | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | फ़ॉन्ट फ़ैमिली नाम प्राप्त करता है (कभी null या खाली नहीं)। |
|
|  | [getStyle()](#getStyle--) | फ़ॉन्ट की शैली प्राप्त करता है: Regular, Bold, Italic, या BoldItalic। |
|
|  | [isEmbedded()](#isEmbedded--) | यह दर्शाता है कि यह फ़ॉन्ट Viewer इंस्टेंस में लोड किए गए दस्तावेज़ के भीतर एम्बेडेड है या नहीं। |
|
|  | [getFormat()](#getFormat--) | फ़ॉन्ट फ़ॉर्मेट प्राप्त करता है (TrueType, OpenType, आदि)। |
|
|  | [getContent()](#getContent--) | फ़ॉन्ट की बाइनरी सामग्री प्राप्त करता है, या यदि फ़ॉन्ट डेटा उपलब्ध नहीं है तो null। |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | निर्दिष्ट राइटर का उपयोग करके इस फ़ॉन्ट जानकारी को CSS @font-face नियम में सीरियलाइज़ करता है। |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट फ़ैमिली नाम प्राप्त करता है (कभी null या खाली नहीं)।


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


फ़ॉन्ट की शैली प्राप्त करता है: Regular, Bold, Italic, या BoldItalic।


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


यह दर्शाता है कि यह फ़ॉन्ट Viewer इंस्टेंस में लोड किए गए दस्तावेज़ के भीतर एम्बेडेड है या नहीं। नोट: स्प्रेडशीट दस्तावेज़ एम्बेडेड फ़ॉन्ट नहीं रख सकते, इसलिए उनके लिए यह हमेशा false लौटाता है।


**Returns:**
boolean
### getFormat() {#getFormat--}
```
public int getFormat()
```


फ़ॉन्ट फ़ॉर्मेट प्राप्त करता है (TrueType, OpenType, आदि)। यदि केवल मेटाडेटा उपलब्ध है, तो FontFormat.Unknown लौटाता है।


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


फ़ॉन्ट की बाइनरी सामग्री प्राप्त करता है, या यदि फ़ॉन्ट डेटा उपलब्ध नहीं है तो null।


**Returns:**
byte[]
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


निर्दिष्ट राइटर का उपयोग करके इस फ़ॉन्ट जानकारी को CSS @font-face नियम में सीरियलाइज़ करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | output | java.io.Writer | CSS लिखने के लिए राइटर (null नहीं होना चाहिए)। |
|

