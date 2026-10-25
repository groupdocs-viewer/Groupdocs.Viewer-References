---
title: "FontStyles"
second_title: "GroupDocs.Viewer Java için API Referansı"
description: "Belge içinde kullanılan yazı tipinin 4 olası stilini temsil eder: Regular, Bold, Italic veya Bold Italic."
type: docs
weight: 13
url: /tr/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Belgede kullanılan yazı tipinin 4 olası stilini temsil eder: Normal, Kalın, İtalik veya Kalın İtalik.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Kalın/italik bayraklarından bir FontStyles örneği oluşturur. |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Bir stil değerini insan tarafından okunabilir bir dizeye dönüştürür. |
|
|  | [getName()](#getName--) | Bu yazı tipi stilinin okunabilir adını döndürür. |
|
|  | [isBold()](#isBold--) | Kalın biti ayarlanmışsa true döndürür. |
|
|  | [isItalic()](#isItalic--) | İtalik biti ayarlanmışsa true döndürür. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Birleşim (C# operatörü +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Fark (C# operatörü -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Bir yazı tipi stil adını FontStyles'a ayrıştırır. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Kalın/italik bayraklarından bir FontStyles örneği oluşturur.


**Parameters:**
| Parametre | Tür | Açıklama |
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


Bir stil değerini insan tarafından okunabilir bir dizeye dönüştürür.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | stil | int | yazı tipi stili değeri |
|

**Returns:**
java.lang.String - yazı tipi stilinin dize temsili

### getName() {#getName--}
```
public String getName()
```


Bu yazı tipi stilinin okunabilir adını döndürür.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Kalın biti ayarlanmışsa true döndürür.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


İtalik biti ayarlanmışsa true döndürür.


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
| Parametre | Tür | Açıklama |
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


Birleşim (C# operatörü +)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ilk | com.groupdocs.viewer.fonts.FontStyles |  |
| ikinci | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Fark (C# operatörü -)


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| çıkacak | com.groupdocs.viewer.fonts.FontStyles |  |
| çıkan | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Bir yazı tipi stil adını FontStyles'a ayrıştırır.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stil | java.lang.String |  |
| ayrıştırıldı | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - başarılı olduğunda true, aksi takdirde false.

