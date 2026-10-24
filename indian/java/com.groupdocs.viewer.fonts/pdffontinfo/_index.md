---
title: "PdfFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "Viewer इंस्टेंस में लोड किए गए PDF डॉक्यूमेंट से एक फ़ॉन्ट की मेटा-जानकारी और बाइनरी डेटा को समाहित करता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.viewer.fonts/pdffontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public class PdfFontInfo implements IFontInfo
```

Viewer इंस्टेंस में लोड किए गए PDF दस्तावेज़ से एक फ़ॉन्ट की मेटा‑सूचना और बाइनरी डेटा को संलग्न करता है।


यह फ़ॉन्ट डॉक्यूमेंट सामग्री में उपयोग किया जाता है और यह या तो:

* embedded inside the PDF document
* or installed in the operating system where GroupDocs.Viewer is running

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)](#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-) | PDF फ़ॉन्ट निष्कर्षण द्वारा उपयोग किया गया आंतरिक कंस्ट्रक्टर। |
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | फ़ॉन्ट फ़ैमिली का नाम प्राप्त करता है। |
|
|  | [getStyle()](#getStyle--) | इस फ़ॉन्ट की शैली प्राप्त करता है। |
|
|  | [isEmbedded()](#isEmbedded--) | वापस करता है कि फ़ॉन्ट PDF डॉक्यूमेंट के भीतर एम्बेडेड है या नहीं। |
|
|  | [isInstalled()](#isInstalled--) | वापस करता है कि फ़ॉन्ट OS में स्थापित है या नहीं। |
|
|  | [getFormat()](#getFormat--) | फ़ॉन्ट का फ़ाइल फ़ॉर्मेट लौटाता है। |
|
|  | [getContent()](#getContent--) | फ़ॉन्ट की बाइनरी सामग्री लौटाता है। |
|
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | इस फ़ॉन्ट को CSS @font-face नियम के रूप में सीरियलाइज़ करता है। |
|
### PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format) {#PdfFontInfo-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-boolean-boolean-byte---int-}
```
public PdfFontInfo(String familyName, FontStyles style, boolean isEmbedded, boolean isInstalled, byte[] content, int format)
```


PDF फ़ॉन्ट निष्कर्षण द्वारा उपयोग किया गया आंतरिक कंस्ट्रक्टर।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | familyName | java.lang.String | फ़ॉन्ट परिवार का नाम |
|
|  | स्टाइल | com.groupdocs.viewer.fonts.FontStyles | शैली (Regular, Bold, Italic, BoldItalic) |
|
|  | isEmbedded | boolean | सही यदि फ़ॉन्ट PDF में एम्बेडेड है। |
|
|  | isInstalled | boolean | सही यदि फ़ॉन्ट OS में स्थापित है। |
|
|  | content | byte[] | बाइनरी फ़ॉन्ट डेटा (nullable) |
|
|  | फ़ॉर्मेट | int | फ़ॉन्ट फ़ाइल फ़ॉर्मेट |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


फ़ॉन्ट फ़ैमिली का नाम प्राप्त करता है।


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


वापस करता है कि फ़ॉन्ट PDF डॉक्यूमेंट के भीतर एम्बेडेड है या नहीं।


**Returns:**
boolean - true यदि एम्बेडेड है

### isInstalled() {#isInstalled--}
```
public boolean isInstalled()
```


वापस करता है कि फ़ॉन्ट OS में स्थापित है या नहीं।


**Returns:**
boolean - true यदि स्थापित है

### getFormat() {#getFormat--}
```
public int getFormat()
```


फ़ॉन्ट का फ़ाइल फ़ॉर्मेट लौटाता है।


**Returns:**
int - फ़ॉन्ट फ़ॉर्मेट enum

### getContent() {#getContent--}
```
public byte[] getContent()
```


फ़ॉन्ट की बाइनरी सामग्री लौटाता है।


**Returns:**
byte[] - बाइट एरे या यदि उपलब्ध नहीं हो तो null

### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


इस फ़ॉन्ट को CSS @font-face नियम के रूप में सीरियलाइज़ करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | output | java.io.Writer | writer जहाँ CSS लिखा जाएगा |
|

