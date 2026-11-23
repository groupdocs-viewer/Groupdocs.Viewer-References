---
title: "FontStyles"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет 4 возможных стиля шрифта, используемого в документе: Regular, Bold, Italic или Bold Italic."
type: docs
weight: 13
url: /ru/java/com.groupdocs.viewer.fonts/fontstyles/
---
**Inheritance:**
java.lang.Object
```
public final class FontStyles
```

Представляет 4 возможных стиля шрифта, используемых в документе: Regular, Bold, Italic или Bold Italic.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FontStyles(boolean isBold, boolean isItalic)](#FontStyles-boolean-boolean-) | Создаёт экземпляр FontStyles из флагов bold/italic. |
|
## Поля

| Поле | Описание |
| --- | --- |
| [Regular](#Regular) |  |
| [Bold](#Bold) |  |
| [Italic](#Italic) |  |
| [BoldItalic](#BoldItalic) |  |
| [REGULAR](#REGULAR) |  |
| [BOLD](#BOLD) |  |
| [ITALIC](#ITALIC) |  |
| [BOLD_ITALIC](#BOLD-ITALIC) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [toString(int style)](#toString-int-) | Преобразует значение стиля в человекочитаемую строку. |
|
|  | [getName()](#getName--) | Возвращает читаемое название этого стиля шрифта. |
|
|  | [isBold()](#isBold--) | Возвращает true, если установлен бит полужирного. |
|
|  | [isItalic()](#isItalic--) | Возвращает true, если установлен бит курсивного. |
|
| [toString()](#toString--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
|  | [combine(FontStyles first, FontStyles second)](#combine-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Объединение (оператор C# +) |
|
|  | [subtract(FontStyles minuend, FontStyles subtrahend)](#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-) | Разность (оператор C# -) |
|
|  | [tryParse(String style, FontStyles[] parsed)](#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---) | Разбирает название стиля шрифта в FontStyles. |
|
### FontStyles(boolean isBold, boolean isItalic) {#FontStyles-boolean-boolean-}
```
public FontStyles(boolean isBold, boolean isItalic)
```


Создаёт экземпляр FontStyles из флагов bold/italic.


**Parameters:**
| Параметр | Тип | Описание |
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


Преобразует значение стиля в человекочитаемую строку.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | стиль | int | значение стиля шрифта |
|

**Returns:**
java.lang.String - строковое представление стиля шрифта

### getName() {#getName--}
```
public String getName()
```


Возвращает читаемое название этого стиля шрифта.


**Returns:**
java.lang.String
### isBold() {#isBold--}
```
public boolean isBold()
```


Возвращает true, если установлен бит полужирного.


**Returns:**
boolean
### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Возвращает true, если установлен бит курсивного.


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
| Параметр | Тип | Описание |
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


Объединение (оператор C# +)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| первый | com.groupdocs.viewer.fonts.FontStyles |  |
| второй | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### subtract(FontStyles minuend, FontStyles subtrahend) {#subtract-com.groupdocs.viewer.fonts.FontStyles-com.groupdocs.viewer.fonts.FontStyles-}
```
public static FontStyles subtract(FontStyles minuend, FontStyles subtrahend)
```


Разность (оператор C# -)


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| уменьшаемое | com.groupdocs.viewer.fonts.FontStyles |  |
| вычитаемое | com.groupdocs.viewer.fonts.FontStyles |  |

**Returns:**
com.groupdocs.viewer.fonts.FontStyles
### tryParse(String style, FontStyles[] parsed) {#tryParse-java.lang.String-com.groupdocs.viewer.fonts.FontStyles---}
```
public static boolean tryParse(String style, FontStyles[] parsed)
```


Разбирает название стиля шрифта в FontStyles.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| стиль | java.lang.String |  |
| разобранный | com.groupdocs.viewer.fonts.FontStyles[] |  |

**Returns:**
boolean - true при успехе, false в противном случае.

