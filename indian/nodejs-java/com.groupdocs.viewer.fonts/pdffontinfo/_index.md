---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "Viewer उदाहरण में लोड किए गए PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा-जानकारी और बाइनरी डेटा को संलग्न करता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा-जानकारी और बाइनरी डेटा को समाहित करता है, जो व्यूअर इंस्टेंस में लोड किया गया है।

यह फ़ॉन्ट दस्तावेज़ सामग्री में उपयोग किया गया है और यह या तो:

 *  embedded inside the PDF document
 *  or installed in the operating system where GroupDocs.Viewer is running
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF फ़ॉन्ट निष्कर्षण द्वारा उपयोग किया गया आंतरिक कंस्ट्रक्टर। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | फ़ॉन्ट परिवार का नाम प्राप्त करता है। |
| [getStyle()](#getStyle--) | इस फ़ॉन्ट की शैली प्राप्त करता है। |
| [isEmbedded()](#isEmbedded--) | वापस देता है कि फ़ॉन्ट PDF दस्तावेज़ के भीतर एम्बेड किया गया है या नहीं। |
| [isInstalled()](#isInstalled--) | वापस देता है कि फ़ॉन्ट ऑपरेटिंग सिस्टम में स्थापित है या नहीं। |
| [getFormat()](#getFormat--) | फ़ॉन्ट के फ़ाइल फ़ॉर्मेट को वापस देता है। |
| [getContent()](#getContent--) | फ़ॉन्ट की बाइनरी सामग्री को वापस देता है। |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | इस फ़ॉन्ट को CSS @font-face नियम के रूप में सीरियलाइज़ करता है। |
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF फ़ॉन्ट निष्कर्षण द्वारा उपयोग किया गया आंतरिक कंस्ट्रक्टर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| familyName | java.lang.String | फ़ॉन्ट परिवार नाम |
| शैली | com.groupdocs.viewer.fonts.FontStyles | शैली (Regular, Bold, Italic, BoldItalic) |
| isEmbedded | boolean | सही यदि फ़ॉन्ट PDF में एम्बेड किया गया है |
| isInstalled | boolean | सही यदि फ़ॉन्ट OS में स्थापित है |
| सामग्री | byte[] | बाइनरी फ़ॉन्ट डेटा (nullable) |
| फ़ॉर्मेट | int | फ़ॉन्ट फ़ाइल फ़ॉर्मेट |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट परिवार का नाम प्राप्त करता है।

**Returns:**
java.lang.String - परिवार नाम स्ट्रिंग (कभी null या खाली नहीं)
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


इस फ़ॉन्ट की शैली प्राप्त करता है।

**Returns:**
com.groupdocs.viewer.fonts.FontStyles - फ़ॉन्ट शैली
### isEmbedded() {#isEmbedded--}
```
public boolean isEmbedded()
```


वापस देता है कि फ़ॉन्ट PDF दस्तावेज़ के भीतर एम्बेड किया गया है या नहीं।

**Returns:**
boolean - सही यदि एम्बेड किया गया
### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


वापस देता है कि फ़ॉन्ट ऑपरेटिंग सिस्टम में स्थापित है या नहीं।

**Returns:**
boolean - सही यदि स्थापित
### getFormat() {#getFormat--}
```
public int getFormat()
```


फ़ॉन्ट के फ़ाइल फ़ॉर्मेट को वापस देता है।

**Returns:**
int - फ़ॉन्ट फ़ॉर्मेट enum
### getContent() {#getContent--}
```
public byte[] getContent()
```


फ़ॉन्ट की बाइनरी सामग्री को वापस देता है।

**Returns:**
byte[] - बाइट एरे या null यदि उपलब्ध नहीं है
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


इस फ़ॉन्ट को CSS @font-face नियम के रूप में सीरियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आउटपुट | java.io.Writer | CSS लिखे जाने वाला writer |

