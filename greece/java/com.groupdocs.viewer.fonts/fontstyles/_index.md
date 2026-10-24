---
title: "FontStyles"
second_title: "GroupDocs.Viewer για Java API Reference"
description: "Αναπαριστά 4 πιθανά στυλ της γραμματοσειράς που χρησιμοποιείται στο έγγραφο: Regular, Bold, Italic ή Bold Italic."
type: docs
weight: 13
url: /el/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Αντιπροσωπεύει 4 πιθανές μορφές γραμματοσειράς, που χρησιμοποιούνται στο έγγραφο: Regular, Bold, Italic ή Bold Italic.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Δημιουργεί ένα αντικείμενο FontStyles από τις σημαίες bold/italic. |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Μετατρέπει μια τιμή στυλ σε αναγνώσιμη από άνθρωπο συμβολοσειρά. |
|
|  | [getName()](#getName--) | Επιστρέφει το αναγνώσιμο όνομα αυτού του στυλ γραμματοσειράς. |
|
|  | [isBold()](#isBold--) | Επιστρέφει true εάν το bold bit είναι ορισμένο. |
|
|  | [isItalic()](#isItalic--) | Επιστρέφει true εάν το italic bit είναι ορισμένο. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Ένωση (C# τελεστής +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Διαφορά (C# τελεστής -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Αναλύει ένα όνομα στυλ γραμματοσειράς σε FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Δημιουργεί ένα αντικείμενο FontStyles από τις σημαίες bold/italic.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Μετατρέπει μια τιμή στυλ σε αναγνώσιμη από άνθρωπο συμβολοσειρά.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | στυλ | int | η τιμή του στυλ γραμματοσειράς |
|

**Returns:**
java.lang.String - μια αναπαράσταση συμβολοσειράς του στυλ γραμματοσειράς

### getName() {#getName--}
```
public String getName()
```


Επιστρέφει το αναγνώσιμο όνομα αυτού του στυλ γραμματοσειράς.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Επιστρέφει true εάν το bold bit είναι ορισμένο.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Επιστρέφει true εάν το italic bit είναι ορισμένο.


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
| Παράμετρος | Τύπος | Περιγραφή |
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


Ένωση (C# τελεστής +)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πρώτο | com.groupdocs.viewer.fonts.FontStyles |  |
| δεύτερο | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Διαφορά (C# τελεστής -)


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αφαιρετέος | com.groupdocs.viewer.fonts.FontStyles |  |
| αφαιρετέος | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Αναλύει ένα όνομα στυλ γραμματοσειράς σε FontStyles.


**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| στυλ | java.lang.String |  |
| αναλυμένο | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true σε περίπτωση επιτυχίας, false διαφορετικά.

