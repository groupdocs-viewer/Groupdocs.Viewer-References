---
title: "WordProcessingOptions"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет параметры для визуализации документов обработки текста."
type: docs
weight: 38
url: /ru/java/com.groupdocs.viewer.options/wordprocessingoptions/
---
**Inheritance:**
java.lang.Object
```
public class WordProcessingOptions
```

Предоставляет параметры для визуализации документов обработки текста.


Класс WordProcessingOptions предоставляет параметры для рендеринга текстовых документов
в компоненте GroupDocs.Viewer. Он инкапсулирует настройки и параметры, которые могут быть использованы
для управления процессом рендеринга и форматом вывода файлов текстовых документов.
Для получения деталей см. [документацию](../https://docs.groupdocs.com/viewer/net/render-word-documents/).


Пример использования:

````

 PngViewOptions pngViewOptions = new PngViewOptions();
 WordProcessingOptions wordProcessingOptions = pngViewOptions.getWordProcessingOptions();
 wordProcessingOptions.setRenderTrackedChanges(true);
 wordProcessingOptions.setLeftMargin(32f);

 try (Viewer viewer = new Viewer("document.docx")) {
     viewer.view(pngViewOptions);
     // Use the viewer object for further operations
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingOptions()](#WordProcessingOptions--) | Инициализирует новый экземпляр |
WordProcessingOptions
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Получает размер страницы для рендеринга файлов HTM и HTML. |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.viewer.options.PageSize-) | Устанавливает размер страницы для рендеринга файлов HTM и HTML. |
|
|  | [isRenderTrackedChanges()](#isRenderTrackedChanges--) | Указывает, включён ли рендеринг отслеживаемых изменений (ревизий). |
|
|  | [setRenderTrackedChanges(boolean value)](#setRenderTrackedChanges-boolean-) | Устанавливает, включён ли рендеринг отслеживаемых изменений (ревизий). |
|
|  | [getLeftMargin()](#getLeftMargin--) | Получает левый отступ страницы для рендеринга HTML. |
|
|  | [setLeftMargin(Double leftMargin)](#setLeftMargin-java.lang.Double-) | Устанавливает левый отступ страницы для рендеринга HTML. |
|
|  | [getRightMargin()](#getRightMargin--) | Получает правый отступ страницы для рендеринга HTML. |
|
|  | [setRightMargin(Double rightMargin)](#setRightMargin-java.lang.Double-) | Устанавливает правый отступ страницы для HTML‑рендеринга. |
|
|  | [getTopMargin()](#getTopMargin--) | Получает верхний отступ страницы для HTML‑рендеринга. |
|
|  | [setTopMargin(Double topMargin)](#setTopMargin-java.lang.Double-) | Устанавливает верхний отступ страницы для HTML‑рендеринга. |
|
|  | [getBottomMargin()](#getBottomMargin--) | Нижний отступ страницы (только для HTML‑рендеринга) |
|
|  | [setBottomMargin(Double bottomMargin)](#setBottomMargin-java.lang.Double-) | Устанавливает нижний отступ страницы для HTML‑рендеринга. |
|
|  | [isEnableOpenTypeFeatures()](#isEnableOpenTypeFeatures--) | Эта опция включает кернинг и другие функции OpenType при рендеринге арабского, ивритского, индийских, латинских или кириллических скриптов. |
|
|  | [setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)](#setEnableOpenTypeFeatures-boolean-) | Эта опция включает кернинг и другие функции OpenType при рендеринге арабского, ивритского, индийских, латинских или кириллических скриптов. |
|
|  | [isUnlinkTableOfContents()](#isUnlinkTableOfContents--) | Указывает, следует ли отключить навигацию по оглавлению при рендеринге в HTML или PDF. |
|
|  | [setUnlinkTableOfContents(boolean unlinkTableOfContents)](#setUnlinkTableOfContents-boolean-) | Устанавливает, следует ли отключить навигацию по оглавлению при рендеринге в HTML или PDF. |
|
|  | [isUpdateFields()](#isUpdateFields--) | Получает значение, определяющее, следует ли обновлять поля определённых типов перед сохранением входного документа WordProcessing в форматы HTML, PDF, PNG или JPEG. |
|
|  | [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) | Устанавливает значение, определяющее, следует ли обновлять поля определённых типов перед сохранением входного документа WordProcessing в форматы HTML, PDF, PNG или JPEG. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Получает горизонтальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [setHorizontalResolution(int horizontalResolution)](#setHorizontalResolution-int-) | Устанавливает горизонтальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Получает вертикальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [setVerticalResolution(int verticalResolution)](#setVerticalResolution-int-) | Устанавливает вертикальное разрешение генерируемых изображений в точках на дюйм. |
|
|  | [getPageNumberLocation()](#getPageNumberLocation--) | Позволяет принудительно применить нумерацию страниц к загруженному документу WordProcessing. |
|
|  | [setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)](#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-) | Позволяет принудительно применить нумерацию страниц к загруженному документу WordProcessing. |
|
|  | [equals(Object o)](#equals-java.lang.Object-) | Проверьте, изменились ли параметры. |
|
|  | [hashCode()](#hashCode--) | {@inheritDoc} |
|
### WordProcessingOptions() {#WordProcessingOptions--}
```
public WordProcessingOptions()
```


Инициализирует новый экземпляр
WordProcessingOptions
класса.
Содержит параметры для рендеринга текстовых документов. Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Получает размер страницы для рендеринга файлов HTM и HTML.


При использовании размера страницы по умолчанию часть содержимого может не помещаться в рамку страницы.
Чтобы разместить содержимое, вы можете установить больший размер страницы, например A3, используя [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Returns:**
[PageSize](../../com.groupdocs.viewer.options/pagesize) - The size of the output page.

### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.viewer.options.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Устанавливает размер страницы для рендеринга файлов HTM и HTML.


При использовании размера страницы по умолчанию часть содержимого может не помещаться в рамку страницы.
Чтобы разместить содержимое, вы можете установить больший размер страницы, например A3, используя [PageSize.A3](../../com.groupdocs.viewer.options/pagesize#A3).


***Note:** The default value is [PageSize.UNSPECIFIED](../../com.groupdocs.viewer.options/pagesize#UNSPECIFIED), which means that a page size set in the page settings (Page Setup) will be used.*


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageSize | [PageSize](../../com.groupdocs.viewer.options/pagesize) | Размер выходной страницы. |
|

### isRenderTrackedChanges() {#isRenderTrackedChanges--}
```
public final boolean isRenderTrackedChanges()
```


Указывает, включён ли рендеринг отслеживаемых изменений (ревизий).
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Returns:**
boolean —  true  если рендеринг отслеживаемых изменений включён,  false  в противном случае.

### setRenderTrackedChanges(boolean value) {#setRenderTrackedChanges-boolean-}
```
public final void setRenderTrackedChanges(boolean value)
```


Устанавливает, включён ли рендеринг отслеживаемых изменений (ревизий).
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#render-tracked-changes).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | value | boolean | true  чтобы включить рендеринг отслеживаемых изменений,  false  чтобы отключить его. |
|

### getLeftMargin() {#getLeftMargin--}
```
public Double getLeftMargin()
```


Получает левый отступ страницы для рендеринга HTML.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double — значение левого отступа страницы.

### setLeftMargin(Double leftMargin) {#setLeftMargin-java.lang.Double-}
```
public void setLeftMargin(Double leftMargin)
```


Устанавливает левый отступ страницы для рендеринга HTML.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | leftMargin | java.lang.Double | Значение левого отступа страницы для установки. |
|

### getRightMargin() {#getRightMargin--}
```
public Double getRightMargin()
```


Получает правый отступ страницы для рендеринга HTML.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - значение правого поля страницы.

### setRightMargin(Double rightMargin) {#setRightMargin-java.lang.Double-}
```
public void setRightMargin(Double rightMargin)
```


Устанавливает правый отступ страницы для HTML‑рендеринга.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | rightMargin | java.lang.Double | Значение правого поля страницы для установки. |
|

### getTopMargin() {#getTopMargin--}
```
public Double getTopMargin()
```


Получает верхний отступ страницы для HTML‑рендеринга.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - значение верхнего поля страницы.

### setTopMargin(Double topMargin) {#setTopMargin-java.lang.Double-}
```
public void setTopMargin(Double topMargin)
```


Устанавливает верхний отступ страницы для HTML‑рендеринга.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | topMargin | java.lang.Double | Верхнее поле страницы для установки. |
|

### getBottomMargin() {#getBottomMargin--}
```
public Double getBottomMargin()
```


Нижний отступ страницы (только для HTML‑рендеринга)
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Returns:**
java.lang.Double - значение нижнего поля страницы.

### setBottomMargin(Double bottomMargin) {#setBottomMargin-java.lang.Double-}
```
public void setBottomMargin(Double bottomMargin)
```


Устанавливает нижний отступ страницы для HTML‑рендеринга.
Подробности см. в [документации](../https://docs.groupdocs.com/viewer/net/render-word-documents/#define-page-margins).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | bottomMargin | java.lang.Double | Нижнее поле страницы для установки. |
|

### isEnableOpenTypeFeatures() {#isEnableOpenTypeFeatures--}
```
public boolean isEnableOpenTypeFeatures()
```


Эта опция включает кернинг и другие функции OpenType при рендеринге арабского, ивритского, индийских, латинских или кириллических скриптов.


**Returns:**
boolean - Истина, если функции OpenType включены, иначе ложь.

### setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures) {#setEnableOpenTypeFeatures-boolean-}
```
public void setEnableOpenTypeFeatures(boolean enableOpenTypeFeatures)
```


Эта опция включает кернинг и другие функции OpenType при рендеринге арабского, ивритского, индийских, латинских или кириллических скриптов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | enableOpenTypeFeatures | boolean | Истина для включения функций OpenType, иначе ложь. |
|

### isUnlinkTableOfContents() {#isUnlinkTableOfContents--}
```
public boolean isUnlinkTableOfContents()
```


Указывает, следует ли отключить навигацию по оглавлению при рендеринге в HTML или PDF. Когда эта опция установлена в true, при рендеринге HTML относительные ссылки из оглавления будут заменены на теги span, что удалит функциональность, но сохранит визуальный вид. При рендеринге PDF оглавление будет отображаться как обычный текст без ссылок.


**Returns:**
boolean - Истина, если навигация по оглавлению отключена; иначе ложь.

### setUnlinkTableOfContents(boolean unlinkTableOfContents) {#setUnlinkTableOfContents-boolean-}
```
public void setUnlinkTableOfContents(boolean unlinkTableOfContents)
```


Устанавливает, следует ли отключить навигацию по оглавлению при рендеринге в HTML или PDF. Когда эта опция установлена в true, при рендеринге HTML относительные ссылки из оглавления будут заменены на теги span, что удалит функциональность, но сохранит визуальный вид. При рендеринге PDF оглавление будет отображаться как обычный текст без ссылок.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | unlinkTableOfContents | boolean | Указывает, следует ли отключить навигацию по оглавлению. |
|

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


Возвращает значение, определяющее, следует ли обновлять поля определённых типов перед сохранением входного документа WordProcessing в форматы HTML, PDF, PNG или JPEG. Значение свойства по умолчанию — true \\u2014 поля будут обновлены перед сохранением.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```


Устанавливает значение, определяющее, следует ли обновлять поля определённых типов перед сохранением входного документа WordProcessing в форматы HTML, PDF, PNG или JPEG. Значение свойства по умолчанию — true \\u2014 поля будут обновлены перед сохранением.


Для получения подробностей см. [документацию](../https://docs.groupdocs.com/viewer/net/render-word-documents/#disable-updating-fields-when-saving).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| updateFields | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public int getHorizontalResolution()
```


Возвращает горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Returns:**
int — горизонтальное разрешение в DPI.

### setHorizontalResolution(int horizontalResolution) {#setHorizontalResolution-int-}
```
public void setHorizontalResolution(int horizontalResolution)
```


Устанавливает горизонтальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | horizontalResolution | int | горизонтальное разрешение в DPI. |
|

### getVerticalResolution() {#getVerticalResolution--}
```
public int getVerticalResolution()
```


Возвращает вертикальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Returns:**
int — вертикальное разрешение в DPI.

### setVerticalResolution(int verticalResolution) {#setVerticalResolution-int-}
```
public void setVerticalResolution(int verticalResolution)
```


Устанавливает вертикальное разрешение генерируемых изображений в точках на дюйм. Эта опция используется только при рендеринге документов WordProcessing в форматы PNG или JPEG.


Значение по умолчанию — 96 DPI. Минимально возможное значение — 72 DPI, максимально возможное значение — 600 DPI.
Если указанное пользователем значение выходит за эти пределы, будет применено минимальное или максимальное возможное значение.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | verticalResolution | int | вертикальное разрешение в DPI. |
|

### getPageNumberLocation() {#getPageNumberLocation--}
```
public WordsPageNumberLocation getPageNumberLocation()
```


Позволяет принудительно применить нумерацию страниц к загруженному документу WordProcessing. По умолчанию используется [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 документ остаётся неизменным.


**Returns:**
[WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) - the page number location.

### setPageNumberLocation(WordsPageNumberLocation pageNumberLocation) {#setPageNumberLocation-com.groupdocs.viewer.options.WordsPageNumberLocation-}
```
public void setPageNumberLocation(WordsPageNumberLocation pageNumberLocation)
```


Позволяет принудительно применить нумерацию страниц к загруженному документу WordProcessing. По умолчанию используется [WordsPageNumberLocation.NOT_APPLY](../../com.groupdocs.viewer.options/wordspagenumberlocation#NOT-APPLY) \\u2014 документ остаётся неизменным.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumberLocation | [WordsPageNumberLocation](../../com.groupdocs.viewer.options/wordspagenumberlocation) | место расположения номера страницы. |
|

### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверьте, изменились ли параметры.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | o | java.lang.Object | Объект для сравнения на равенство. |
|

**Returns:**
boolean -  true  если параметры равны указанному объекту,  false  в противном случае.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Вычисляет значение хеш‑кода для этого объекта. Хеш‑код основан на
внутреннем состоянии объекта и используется в структурах данных, основанных на хешах
таких как хеш‑карты и хеш‑множества.
***Note:** This method overrides the default implementation of the hashCode() method defined in the Object class.*


**Returns:**
int - значение хеш‑кода для этого объекта.

