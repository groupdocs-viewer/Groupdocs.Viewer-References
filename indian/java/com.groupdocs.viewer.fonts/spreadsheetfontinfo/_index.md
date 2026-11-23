---
title: "SpreadsheetFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer इंस्टेंस में लोड किए गए Spreadsheet दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.viewer.fonts/spreadsheetfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class SpreadsheetFontInfo implements IFontInfo
```

Viewer इंस्टेंस में लोड किए गए Spreadsheet दस्तावेज़ से एक फ़ॉन्ट की मेटा जानकारी और बाइनरी डेटा को संलग्न करता है। Spreadsheet दस्तावेज़ों में एम्बेडेड फ़ॉन्ट नहीं हो सकते, इसलिए यदि यह फ़ॉन्ट Viewer.getAllFonts() मेथड द्वारा लौटाया जाता है, तो यह उस ऑपरेटिंग सिस्टम में स्थापित होता है जहाँ GroupDocs.Viewer चल रहा है।

## Methods

| Method | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | फ़ॉन्ट का फ़ैमिली नाम, बिना शैली के, कभी भी null या खाली नहीं। |
|
|  | [getStyle()](#getStyle--) | इस फ़ॉन्ट की शैली — Regular, Bold, Italic, या BoldItalic हो सकती है। |
|
|  | [isStrikeout()](#isStrikeout--) | यह दर्शाता है कि फ़ॉन्ट पर एकल स्ट्राइकआउट है या नहीं। |
|
|  | [isUnderline()](#isUnderline--) | यह दर्शाता है कि फ़ॉन्ट में अंडरलाइन है या नहीं। |
|
|  | [getColor()](#getColor--) | इस फ़ॉन्ट का रंग। |
|
|  | [getCharset()](#getCharset--) | इस फ़ॉन्ट का कैरेक्टर सेट। |
|
|  | [getContent()](#getContent--) | इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। |
|
|  | [getFormat()](#getFormat--) | इस फ़ॉन्ट का फ़ॉर्मेट। |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में सीरियलाइज़ करता है और इसे निर्दिष्ट राइटर में लिखता है। |
|
### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट का फ़ैमिली नाम, बिना शैली के, कभी भी null या खाली नहीं।


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


इस फ़ॉन्ट की शैली — Regular, Bold, Italic, या BoldItalic हो सकती है।


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### isStrikeout() {#isStrikeout--}
```
public boolean isStrikeout()
```


यह दर्शाता है कि फ़ॉन्ट पर एकल स्ट्राइकआउट है या नहीं।


**Returns:**
boolean
### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


यह दर्शाता है कि फ़ॉन्ट में अंडरलाइन है या नहीं।


**Returns:**
boolean
### getColor() {#getColor--}
```
public Argb32Color getColor()
```


इस फ़ॉन्ट का रंग।


**Returns:**
[Argb32Color](../../com.groupdocs.viewer.drawing/argb32color)
### getCharset() {#getCharset--}
```
public int getCharset()
```


इस फ़ॉन्ट का कैरेक्टर सेट।


**Returns:**
int
### getContent() {#getContent--}
```
public byte[] getContent()
```


इस फ़ॉन्ट की सामग्री बाइट एरे के रूप में। यदि केवल मेटा जानकारी उपलब्ध है तो यह null हो सकता है।


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


इस फ़ॉन्ट का फ़ॉर्मेट।


**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


इस फ़ॉन्ट जानकारी को @font-face एट-रूल के रूप में सीरियलाइज़ करता है और इसे निर्दिष्ट राइटर में लिखता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | output | java.io.Writer | सीरियलाइज़्ड टेक्स्ट डेटा लिखने के लिए डिवाइस। |
|

