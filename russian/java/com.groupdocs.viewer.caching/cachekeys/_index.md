---
title: "CacheKeys"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Предоставляет методы для получения уникального идентификатора записи кэша."
type: docs
weight: 10
url: /ru/java/com.groupdocs.viewer.caching/cachekeys/
---
**Inheritance:**
java.lang.Object
```
public class CacheKeys
```

Предоставляет методы для получения уникального идентификатора записи кэша.


Класс позволяет генерировать ключи кэша на основе различных параметров, таких как путь к документу, параметры рендеринга и имя ресурса.
Эти ключи кэша могут использоваться для сохранения и получения кэшированных данных для эффективного рендеринга документов.


Пример использования:

````

 // Generate a cache key for a file
 String fileKey = CacheKeys.getFileKey("filename.pdf");

 // Generate a cache key for a page
 String pageKey = CacheKeys.getPageKey(pageNumber, FileType.HTML.getExtension());

 // Generate a cache key for a resource
 Resource resource = new Resource("styles.css", false);
 String pageKey = CacheKeys.getResourceKey(pageNumber, resource);
 
````


## Поля

| Поле | Описание |
| --- | --- |
| [PAGE_NUMBER](#PAGE-NUMBER) |  |
## Методы

| Метод | Описание |
| --- | --- |
|  | [getAttachmentsKey()](#getAttachmentsKey--) | Возвращает уникальный идентификатор записи кэша, представляющей коллекцию объектов [Attachment](../../com.groupdocs.viewer.results/attachment). |
|
|  | [getAttachmentKey(String attachmentId)](#getAttachmentKey-java.lang.String-) | Получает уникальный идентификатор записи кэша, представляющей файл вложения. |
|
|  | [getViewInfoKey()](#getViewInfoKey--) | Получает уникальный идентификатор записи кэша, представляющей объект [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileInfoKey()](#getFileInfoKey--) | Получает уникальный идентификатор записи кэша, представляющей объект [ViewInfo](../../com.groupdocs.viewer.results/viewinfo). |
|
|  | [getFileKey(String extension)](#getFileKey-java.lang.String-) | Получает уникальный идентификатор записи кэша, представляющей файл. |
|
|  | [getPageKey(int pageNumber, String extension)](#getPageKey-int-java.lang.String-) | Получает уникальный идентификатор записи кэша, представляющей файл страницы. |
|
|  | [getResourceKey(int pageNumber, Resource resource)](#getResourceKey-int-com.groupdocs.viewer.results.Resource-) | Возвращает уникальный идентификатор записи кэша, представляющей объект [Resource](../../com.groupdocs.viewer.results/resource). |
|
|  | [getResourceFilter(int pageNumber)](#getResourceFilter-int-) | Возвращает строку фильтра для поиска записей кэша, представляющих объекты [Resource](../../com.groupdocs.viewer.results/resource). |
|
### PAGE_NUMBER {#PAGE-NUMBER}
```
public static final String PAGE_NUMBER
```


### getAttachmentsKey() {#getAttachmentsKey--}
```
public static String getAttachmentsKey()
```


Возвращает уникальный идентификатор записи кэша, представляющей коллекцию объектов [Attachment](../../com.groupdocs.viewer.results/attachment).


**Returns:**
java.lang.String — уникальный идентификатор записи кэша вложений.

### getAttachmentKey(String attachmentId) {#getAttachmentKey-java.lang.String-}
```
public static String getAttachmentKey(String attachmentId)
```


Получает уникальный идентификатор записи кэша, представляющей файл вложения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | attachmentId | java.lang.String | Уникальный идентификатор вложения (в контексте одного файла). |
|

**Returns:**
java.lang.String — уникальный идентификатор записи кэша файла вложения.

### getViewInfoKey() {#getViewInfoKey--}
```
public static String getViewInfoKey()
```


Получает уникальный идентификатор записи кэша, представляющей объект [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String — уникальный идентификатор записи кэша.

### getFileInfoKey() {#getFileInfoKey--}
```
public static String getFileInfoKey()
```


Получает уникальный идентификатор записи кэша, представляющей объект [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).


**Returns:**
java.lang.String — уникальный идентификатор записи кэша, представляющей объект [ViewInfo](../../com.groupdocs.viewer.results/viewinfo).

### getFileKey(String extension) {#getFileKey-java.lang.String-}
```
public static String getFileKey(String extension)
```


Получает уникальный идентификатор записи кэша, представляющей файл.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | расширение | java.lang.String | Суффикс имени файла (включая точку ".") например ".doc". |
|

**Returns:**
java.lang.String - уникальный идентификатор записи кэша, представляющей файл.

### getPageKey(int pageNumber, String extension) {#getPageKey-int-java.lang.String-}
```
public static String getPageKey(int pageNumber, String extension)
```


Получает уникальный идентификатор записи кэша, представляющей файл страницы.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы. |
|
|  | расширение | java.lang.String | Суффикс имени файла (включая точку ".") например ".doc". |
|

**Returns:**
java.lang.String - уникальный идентификатор записи кэша, представляющей файл страницы.

### getResourceKey(int pageNumber, Resource resource) {#getResourceKey-int-com.groupdocs.viewer.results.Resource-}
```
public static String getResourceKey(int pageNumber, Resource resource)
```


Возвращает уникальный идентификатор записи кэша, представляющей объект [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы. |
|
|  | resource | [Resource](../../com.groupdocs.viewer.results/resource) | HTML-ресурс. |
|

**Returns:**
java.lang.String — уникальный идентификатор записи кэша.

### getResourceFilter(int pageNumber) {#getResourceFilter-int-}
```
public static String getResourceFilter(int pageNumber)
```


Возвращает строку фильтра для поиска записей кэша, представляющих объекты [Resource](../../com.groupdocs.viewer.results/resource).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы. |
|

**Returns:**
java.lang.String - строка фильтра для поиска записей кэша.

