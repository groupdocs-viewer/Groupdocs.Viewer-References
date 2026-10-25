---
title: "FolderFontSource"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Представляет папку, содержащую шрифты TrueType."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.fonts/folderfontsource/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.fonts.FontSource](../../com.groupdocs.viewer.fonts/fontsource), com.aspose.ms.System.IEquatable
```
public final class FolderFontSource implements FontSource, System.IEquatable<FolderFontSource>
```

Представляет папку, содержащую шрифты TrueType.


Класс FolderFontSource используется для указания расположения папки, содержащей шрифты TrueType.
Он позволяет API GroupDocs.Viewer получать доступ к шрифтам, хранящимся в указанной папке, для целей рендеринга документов.


Пример использования:

````

 FontSettings.setFontSources(new FolderFontSource("/path/to/fonts/folder", SearchOption.ALL_FOLDERS));
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [FolderFontSource(String folderPath, SearchOption searchOption)](#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-) | Инициализирует новый экземпляр |
FolderFontSource
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isEqualTo(FolderFontSource left, FolderFontSource right)](#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, являются ли два |
FolderFontSource
объекты одинаковы.
|
|  | [isNotEqualTo(FolderFontSource left, FolderFontSource right)](#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, являются ли два |
FolderFontSource
объекты не одинаковы.
|
|  | [getFolderPath()](#getFolderPath--) | Получает путь к папке, содержащей шрифты TrueType. |
|
|  | [getSearchOption()](#getSearchOption--) | Получает параметр поиска, указывающий, искать ли только текущую папку или текущую папку и все подпапки. |
|
|  | [isRecursive()](#isRecursive--) | Проверяет, будет ли поиск шрифтов выполнен рекурсивно. |
|
|  | [equals(FolderFontSource other)](#equals-com.groupdocs.viewer.fonts.FolderFontSource-) | Определяет, является ли текущий |
FolderFontSource
совпадает с указанным
FolderFontSource
объектом.
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Определяет, является ли текущий |
FolderFontSource
совпадает с указанным объектом.
|
|  | [hashCode()](#hashCode--) | Возвращает хеш-код для текущего |
FolderFontSource
объектом.
|
|  | [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
|
### FolderFontSource(String folderPath, SearchOption searchOption) {#FolderFontSource-java.lang.String-com.groupdocs.viewer.fonts.SearchOption-}
```
public FolderFontSource(String folderPath, SearchOption searchOption)
```


Инициализирует новый экземпляр
FolderFontSource
класса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | folderPath | java.lang.String | Путь к папке, содержащей шрифты TrueType. |
|
|  | searchOption | [SearchOption](../../com.groupdocs.viewer.fonts/searchoption) | Указывает, следует ли искать в текущей папке или в текущей папке и всех вложенных подпапках. |
|

### isEqualTo(FolderFontSource left, FolderFontSource right) {#isEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isEqualTo(FolderFontSource left, FolderFontSource right)
```


Определяет, являются ли два
FolderFontSource
объекты одинаковы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Левый  FolderFontSource  объект. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Правый  FolderFontSource  объект. |
|

**Returns:**
boolean -  true  если оба  FolderFontSource  объекта одинаковы; иначе,  false .

### isNotEqualTo(FolderFontSource left, FolderFontSource right) {#isNotEqualTo-com.groupdocs.viewer.fonts.FolderFontSource-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public static boolean isNotEqualTo(FolderFontSource left, FolderFontSource right)
```


Определяет, являются ли два
FolderFontSource
объекты не одинаковы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | left | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Левый  FolderFontSource  объект. |
|
|  | right | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Правый  FolderFontSource  объект. |
|

**Returns:**
boolean -  true  если оба  FolderFontSource  объекта различаются; иначе,  false .

### getFolderPath() {#getFolderPath--}
```
public String getFolderPath()
```


Получает путь к папке, содержащей шрифты TrueType.


**Returns:**
java.lang.String - путь к папке, содержащей шрифты TrueType.

### getSearchOption() {#getSearchOption--}
```
public SearchOption getSearchOption()
```


Получает параметр поиска, указывающий, искать ли только текущую папку или текущую папку и все подпапки.


**Returns:**
[SearchOption](../../com.groupdocs.viewer.fonts/searchoption) - the search option.

### isRecursive() {#isRecursive--}
```
public boolean isRecursive()
```


Проверяет, будет ли поиск шрифтов выполнен рекурсивно.


**Returns:**
boolean -  true  если шрифты будут искаться рекурсивно,  false  иначе.

### equals(FolderFontSource other) {#equals-com.groupdocs.viewer.fonts.FolderFontSource-}
```
public boolean equals(FolderFontSource other)
```


Определяет, является ли текущий
FolderFontSource
совпадает с указанным
FolderFontSource
объектом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | other | [FolderFontSource](../../com.groupdocs.viewer.fonts/folderfontsource) | Объект для сравнения с текущим  FolderFontSource  объектом. |
|

**Returns:**
boolean -  true  если оба  FolderFontSource  объекта одинаковы; иначе,  false

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Определяет, является ли текущий
FolderFontSource
совпадает с указанным объектом.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | o | java.lang.Object | Объект для сравнения с текущим  FolderFontSource  объектом. |
|

**Returns:**
boolean -  true  если параметр  obj  имеет тип  FolderFontSource  и совпадает с текущим  FolderFontSource  объектом; иначе,  false

### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для текущего
FolderFontSource
объектом.


**Returns:**
int - хеш-код для текущего  FolderFontSource  объекта.

### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.


**Returns:**
java.lang.String — строка, представляющая текущий объект.

