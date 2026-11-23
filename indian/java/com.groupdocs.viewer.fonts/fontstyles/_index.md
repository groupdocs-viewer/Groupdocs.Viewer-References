---
title: "FontStyles"
second_title: "GroupDocs.Viewer for Java API Reference"
description: "दस्तावेज़ में उपयोग किए गए फ़ॉन्ट के 4 संभावित शैलियों को दर्शाता है: Regular, Bold, Italic या Bold Italic।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

दस्तावेज़ में उपयोग किए जाने वाले फ़ॉन्ट के 4 संभावित शैलियों का प्रतिनिधित्व करता है: रेगुलर, बोल्ड, इटैलिक, या बोल्ड इटैलिक।

## Constructors

| Constructor | विवरण |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | bold/italic फ़्लैग्स से एक FontStyles इंस्टेंस बनाता है। |
|
## Fields

| Field | विवरण |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Methods

| Method | विवरण |
| --- | --- |
|  | [toString(int style)](#toString-int-) | स्टाइल मान को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है। |
|
|  | [getName()](#getName--) | इस फ़ॉन्ट शैली का पठनीय नाम लौटाता है। |
|
|  | [isBold()](#isBold--) | यदि बोल्ड बिट सेट है तो true लौटाता है। |
|
|  | [isItalic()](#isItalic--) | यदि इटैलिक बिट सेट है तो true लौटाता है। |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | यूनियन (C# ऑपरेटर +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | अंतर (C# ऑपरेटर -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | फ़ॉन्ट शैली नाम को FontStyles में पार्स करता है। |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


bold/italic फ़्लैग्स से एक FontStyles इंस्टेंस बनाता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| isBold | boolean |  |
| isItalic | boolean |  |

### Regular {#Regular}
```
public static final int Regular
```


### Bold {#Bold}
```
public static final int Bold
```


### Italic {#Italic}
```
public static final int Italic
```


### BoldItalic {#BoldItalic}
```
public static final int BoldItalic
```


### REGULAR {#REGULAR}
```
public static final FontStyles REGULAR
```


### BOLD {#BOLD}
```
public static final FontStyles BOLD
```


### ITALIC {#ITALIC}
```
public static final FontStyles ITALIC
```


### BOLD_ITALIC {#BOLD-ITALIC}
```
public static final FontStyles BOLD_ITALIC
```


### toString(int style) {#toString-int-}
```
public static String toString(int style)
```


स्टाइल मान को मानव-पठनीय स्ट्रिंग में परिवर्तित करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्टाइल | int | फ़ॉन्ट शैली मान |
|

**Returns:**
java.lang.String - फ़ॉन्ट शैली का स्ट्रिंग प्रतिनिधित्व

### getName() {#getName--}
```
public String getName()
```


इस फ़ॉन्ट शैली का पठनीय नाम लौटाता है।


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


यदि बोल्ड बिट सेट है तो true लौटाता है।


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


यदि इटैलिक बिट सेट है तो true लौटाता है।


**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




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
### combine(FontStyles first, FontStyles second) {#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles combine(FontStyles first, FontStyles second)
```


यूनियन (C# ऑपरेटर +)


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| पहला | com.groupdocs.viewer.fonts.FontStyles |  |
| दूसरा | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


अंतर (C# ऑपरेटर -)


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| घटाने वाला | com.groupdocs.viewer.fonts.FontStyles |  |
| घटाया जाने वाला | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


फ़ॉन्ट शैली नाम को FontStyles में पार्स करता है।


**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्टाइल | java.lang.String |  |
| पार्स किया गया | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - सफलता पर true, अन्यथा false.

