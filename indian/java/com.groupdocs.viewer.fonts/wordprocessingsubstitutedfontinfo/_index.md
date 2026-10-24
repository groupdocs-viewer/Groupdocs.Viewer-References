---
title: "WordProcessingSubstitutedFontInfo"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "GroupDocs.Viewer के माध्यम से वर्डप्रोसेसिंग दस्तावेज़ में उपयोग किए गए एक प्रतिस्थापित फ़ॉन्ट की मेटा‑डेटा और बाइनरी डेटा को संलग्न करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.viewer.fonts/wordprocessingsubstitutedfontinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.groupdocs.viewer.fonts.IFontInfo
```
public final class WordProcessingSubstitutedFontInfo implements IFontInfo
```

एक WordProcessing दस्तावेज़ में GroupDocs.Viewer के माध्यम से उपयोग किए गए एक प्रतिस्थापित फ़ॉन्ट के मेटाडेटा और बाइनरी डेटा को संलग्न करता है। अपरिवर्तनीय क्लास।

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)](#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-) | सभी फ़ील्ड को प्रारंभ करने के लिए कन्स्ट्रक्टर। |
|
## Methods

| Method | विवरण |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | प्रतिस्थापित फ़ॉन्ट का फ़ैमिली नाम लौटाता है (कभी null नहीं)। |
|
|  | [getOriginalFamilyName()](#getOriginalFamilyName--) | मूल फ़ॉन्ट का फ़ैमिली नाम लौटाता है (कभी null नहीं)। |
|
|  | [getStyle()](#getStyle--) | मूल फ़ॉन्ट की शैली लौटाता है। |
|
|  | [getContent()](#getContent--) | प्रतिस्थापित फ़ॉन्ट की बाइनरी सामग्री लौटाता है (कभी null नहीं)। |
|
|  | [getFormat()](#getFormat--) | प्रतिस्थापित फ़ॉन्ट का फ़ॉन्ट फ़ॉर्मेट लौटाता है। |
|
|  | [toString()](#toString--) | इस प्रतिस्थापित फ़ॉन्ट का वर्णन करने वाली स्ट्रिंग लौटाता है: "original-name -> substituted-name style, format" |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | मूल फ़ैमिली, प्रतिस्थापित फ़ैमिली और शैली पर आधारित समानता। |
|
| [hashCode()](#hashCode--) |  |
|  | [serializeToCss(Writer output)](#serializeToCss-java.io.Writer-) | उपयोगिता विधि का उपयोग करके इस फ़ॉन्ट को @font-face CSS नियम के रूप में सीरियलाइज़ करें। |
|
### WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format) {#WordProcessingSubstitutedFontInfo-java.lang.String-java.lang.String-com.groupdocs.viewer.fonts.FontStyles-byte---int-}
```
public WordProcessingSubstitutedFontInfo(String originalFamilyName, String substitutedFamilyName, FontStyles style, byte[] content, int format)
```


सभी फ़ील्ड को प्रारंभ करने के लिए कन्स्ट्रक्टर।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | originalFamilyName | java.lang.String | मूल फ़ॉन्ट नाम (सिस्टम पर नहीं मिला) |
|
|  | substitutedFamilyName | java.lang.String | प्रतिस्थापित फ़ॉन्ट नाम (उपलब्ध) |
|
|  | स्टाइल | com.groupdocs.viewer.fonts.FontStyles | फ़ॉन्ट शैली (Regular, Bold, Italic, BoldItalic) |
|
|  | content | byte[] | प्रतिस्थापित फ़ॉन्ट की बाइनरी सामग्री (कभी null नहीं) |
|
|  | फ़ॉर्मेट | int | फ़ॉन्ट फ़ॉर्मेट (TrueType, OpenType, आदि)। |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


प्रतिस्थापित फ़ॉन्ट का फ़ैमिली नाम लौटाता है (कभी null नहीं)।


**Returns:**
java.lang.String
### getOriginalFamilyName() {#getOriginalFamilyName--}
```
public String getOriginalFamilyName()
```


मूल फ़ॉन्ट का फ़ैमिली नाम लौटाता है (कभी null नहीं)।


**Returns:**
java.lang.String
### getStyle() {#getStyle--}
```
public FontStyles getStyle()
```


मूल फ़ॉन्ट की शैली लौटाता है।


**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### getContent() {#getContent--}
```
public byte[] getContent()
```


प्रतिस्थापित फ़ॉन्ट की बाइनरी सामग्री लौटाता है (कभी null नहीं)।


**Returns:**
byte[]
### getFormat() {#getFormat--}
```
public int getFormat()
```


प्रतिस्थापित फ़ॉन्ट का फ़ॉन्ट फ़ॉर्मेट लौटाता है।


**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


इस प्रतिस्थापित फ़ॉन्ट का वर्णन करने वाली स्ट्रिंग लौटाता है: "original-name -> substituted-name style, format"


**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


मूल फ़ैमिली, प्रतिस्थापित फ़ैमिली और शैली पर आधारित समानता। HashSet या HashMap जैसे C# IEqualityComparer में उपयोग के लिए आवश्यक।


**Parameters:**
| Parameter | Type | विवरण |
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


उपयोगिता विधि का उपयोग करके इस फ़ॉन्ट को @font-face CSS नियम के रूप में सीरियलाइज़ करें।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| output | java.io.Writer |  |

