---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Node.js via Java API Reference"
description: "GroupDocs.Viewer के माध्यम से वर्डप्रोसेसिंग दस्तावेज़ में उपयोग किए गए एक प्रतिस्थापित फ़ॉन्ट की मेटाडाटा और बाइनरी डेटा को समाहित करता है।"
type: docs
weight: 18
url: /hi/nodejs-java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

एक WordProcessing दस्तावेज़ में GroupDocs.Viewer के माध्यम से उपयोग किए गए एक substituted फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को समाहित करता है। Immutable class.
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | सभी फ़ील्ड को प्रारंभ करने के लिए Constructor। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | substituted फ़ॉन्ट का परिवार नाम लौटाता है (कभी null नहीं)। |
| [getOriginalFamilyName()](#getOriginalFamilyName--) | original फ़ॉन्ट का परिवार नाम लौटाता है (कभी null नहीं)। |
| [getStyle()](#getStyle--) | original फ़ॉन्ट की शैली लौटाता है। |
| [getContent()](#getContent--) | substituted फ़ॉन्ट की बाइनरी सामग्री लौटाता है (कभी null नहीं)। |
| [getFormat()](#getFormat--) | substituted फ़ॉन्ट का फ़ॉन्ट फ़ॉर्मेट लौटाता है। |
| [toString()](#toString--) | इस substituted फ़ॉन्ट का वर्णन करने वाली स्ट्रिंग लौटाता है: "original-name -> substituted-name style, format" |
| [equals(Object obj)](#equals-java.lang.Object-) | original परिवार, substituted परिवार और शैली के आधार पर समानता। |
| [hashCode()](#hashCode--) |  |
| [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | एक utility method का उपयोग करके इस फ़ॉन्ट को @font-face CSS नियम के रूप में serialize करें। |
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


सभी फ़ील्ड को प्रारंभ करने के लिए Constructor।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| originalFamilyName | java.lang.String | original फ़ॉन्ट नाम (सिस्टम पर नहीं मिला) |
| substitutedFamilyName | java.lang.String | substituted फ़ॉन्ट नाम (उपलब्ध) |
| शैली | com.groupdocs.viewer.fonts.FontStyles | फ़ॉन्ट शैली (Regular, Bold, Italic, BoldItalic) |
| सामग्री | byte[] | substituted फ़ॉन्ट की बाइनरी सामग्री (कभी null नहीं) |
| फ़ॉर्मेट | int | फ़ॉन्ट फ़ॉर्मेट (TrueType, OpenType, आदि) |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


substituted फ़ॉन्ट का परिवार नाम लौटाता है (कभी null नहीं)।

**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


original फ़ॉन्ट का परिवार नाम लौटाता है (कभी null नहीं)।

**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


original फ़ॉन्ट की शैली लौटाता है।

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


substituted फ़ॉन्ट की बाइनरी सामग्री लौटाता है (कभी null नहीं)।

**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


substituted फ़ॉन्ट का फ़ॉन्ट फ़ॉर्मेट लौटाता है।

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


इस substituted फ़ॉन्ट का वर्णन करने वाली स्ट्रिंग लौटाता है: "original-name -> substituted-name style, format"

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


original परिवार, substituted परिवार और शैली के आधार पर समानता। HashSet या HashMap जैसे C\# IEqualityComparer में उपयोग के लिए आवश्यक।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### serializeToCss(Writer output) {#serializeToCss-java.io.Writer-}
```
public void serializeToCss(Writer output)
```


एक utility method का उपयोग करके इस फ़ॉन्ट को @font-face CSS नियम के रूप में serialize करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आउटपुट | java.io.Writer |  |

