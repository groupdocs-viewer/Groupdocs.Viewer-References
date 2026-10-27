---
title: "FolderFontSource"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет папку, содержащую шрифты TrueType."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Представляет папку, содержащую шрифты TrueType.

Класс FolderFontSource используется для указания расположения папки, содержащей шрифты TrueType. Он позволяет API GroupDocs.Viewer получать доступ к шрифтам, хранящимся в указанной папке, для целей рендеринга документов.

Пример использования:

```

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Инициализирует новый экземпляр класса FolderFontSource. |
## Методы

| Метод | Описание |
| --- | --- |
| [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, являются ли два объекта FolderFontSource одинаковыми. |
| [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, не являются ли два объекта FolderFontSource одинаковыми. |
| [getFolderPath()](#getFolderPath--) | Возвращает путь к папке, содержащей шрифты TrueType. |
| [getSearchOption()](#getSearchOption--) | Возвращает параметр поиска, указывающий, искать ли только текущую папку или текущую папку и все подпапки. |
| [isRecursive()](#isRecursive--) | Проверяет, будет ли поиск шрифтов выполнен рекурсивно. |
| [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, является ли текущий объект FolderFontSource тем же, что и указанный объект FolderFontSource. |
| [equals(Object o)](#equals-java.lang.Object-) | Определяет, является ли текущий объект FolderFontSource тем же, что и указанный объект. |
| [hashCode()](#hashCode--) | Возвращает хеш-код текущего объекта FolderFontSource. |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Инициализирует новый экземпляр класса FolderFontSource.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| folderPath | java.lang.String | Путь к папке, содержащей шрифты TrueType. |
| searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Указывает, искать ли текущую папку или текущую папку и все подпапки. |

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Определяет, являются ли два объекта FolderFontSource одинаковыми.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Левый объект FolderFontSource. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Правый объект FolderFontSource. |

**Returns:**
boolean - true, если оба объекта FolderFontSource одинаковы; иначе false.
### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Определяет, не являются ли два объекта FolderFontSource одинаковыми.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Левый объект FolderFontSource. |
| right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Правый объект FolderFontSource. |

**Returns:**
boolean - true, если оба объекта FolderFontSource не одинаковы; иначе false.
### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Возвращает путь к папке, содержащей шрифты TrueType.

**Returns:**
java.lang.String - путь к папке, содержащей шрифты TrueType.
### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Возвращает параметр поиска, указывающий, искать ли только текущую папку или текущую папку и все подпапки.

**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.
### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Проверяет, будет ли поиск шрифтов выполнен рекурсивно.

**Returns:**
boolean - true, если поиск шрифтов будет выполнен рекурсивно, иначе false.
### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Определяет, является ли текущий объект FolderFontSource тем же, что и указанный объект FolderFontSource.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Объект для сравнения с текущим объектом FolderFontSource. |

**Returns:**
boolean - true, если оба объекта FolderFontSource одинаковы; иначе false.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Определяет, является ли текущий объект FolderFontSource тем же, что и указанный объект.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Объект для сравнения с текущим объектом FolderFontSource. |

**Returns:**
boolean - true, если параметр obj имеет тип FolderFontSource и является тем же, что и текущий объект FolderFontSource; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код текущего объекта FolderFontSource.

**Returns:**
int - хеш-код текущего объекта FolderFontSource.
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String - строка, представляющая текущий объект.
