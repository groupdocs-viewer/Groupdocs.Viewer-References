---
title: "FileCache"
second_title: "GroupDocs.Viewer для Node.js через Java API Reference"
description: "Представляет локальный кэш на диске."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.viewer.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.viewer.caching.Cache](../../com.groupdocs.viewer.caching/cache)
```
public class FileCache implements Cache
```

Представляет локальный кэш на диске.

Класс FileCache представляет локальный дисковый кэш в компоненте GroupDocs.Viewer. Он предоставляет возможности для сохранения и получения кэшированных данных на диске для эффективного рендеринга документов.

Пример использования:

```

 FileCache fileCache = new FileCache(cachePath, cacheSubFolder);

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setCache(fileCache);

 try (Viewer viewer = new Viewer(documentPath, viewerSettings)) {
     // Use the viewer object for document rendering
 }
 
```

Чтобы использовать FileCache, необходимо создать экземпляр этого класса и передать его объекту ViewerSettings. Затем объект Viewer будет использовать FileCache для кэширования при рендеринге документов.

***Note:** The FileCache is just one of the cache implementations provided by GroupDocs.Viewer. You can also implement your own custom cache by implementing the Cache interface.*
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | Создаёт новый экземпляр класса FileCache. |
| [FileCache(Path cachePath)](#FileCache-java.nio.file.Path-) | Создаёт новый экземпляр класса FileCache. |
| [FileCache(String cachePath, String cacheSubFolder)](#FileCache-java.lang.String-java.lang.String-) | Создаёт новый экземпляр класса FileCache. |
| [FileCache(Path cachePath, String cacheSubFolder)](#FileCache-java.nio.file.Path-java.lang.String-) | Создаёт новый экземпляр класса FileCache. |
## Поля

| Поле | Описание |
| --- | --- |
| [CACHE_PATH](#CACHE-PATH) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCachePath()](#getCachePath--) | Получает относительный или абсолютный путь к папке кэша. |
| [getCacheSubFolder()](#getCacheSubFolder--) | Подпапка, добавляемая к пути кэша. |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Сериализует данные на локальный диск. |
| [<T>get(String key, Class<T> clazz)](#-T-get-java.lang.String-java.lang.Class-T--) | Десериализует данные, связанные с этим ключом, если они присутствуют. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Возвращает все имена файлов, содержащие фильтр в имени файла. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Создаёт новый экземпляр класса FileCache.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cachePath | java.lang.String | Относительный или абсолютный путь, где будет храниться кэш документов. |

### FileCache(Path cachePath) {#FileCache-java.nio.file.Path-}
```
public FileCache(Path cachePath)
```


Создаёт новый экземпляр класса FileCache.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Относительный или абсолютный путь, где будет храниться кэш документов. |

### FileCache(String cachePath, String cacheSubFolder) {#FileCache-java.lang.String-java.lang.String-}
```
public FileCache(String cachePath, String cacheSubFolder)
```


Создаёт новый экземпляр класса FileCache.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cachePath | java.lang.String | Относительный или абсолютный путь, где будет храниться кэш документов. |
| cacheSubFolder | java.lang.String | Подпапка, которую следует добавить к cachePath. |

### FileCache(Path cachePath, String cacheSubFolder) {#FileCache-java.nio.file.Path-java.lang.String-}
```
public FileCache(Path cachePath, String cacheSubFolder)
```


Создаёт новый экземпляр класса FileCache.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| cachePath | java.nio.file.Path | Относительный или абсолютный путь, где будет храниться кэш документов. |
| cacheSubFolder | java.lang.String | Подпапка, которую следует добавить к cachePath. |

### CACHE_PATH {#CACHE-PATH}
```
public static final String CACHE_PATH
```


### getCachePath() {#getCachePath--}
```
public final String getCachePath()
```


Получает относительный или абсолютный путь к папке кэша.

**Returns:**
java.lang.String - Путь к папке кэша.
### getCacheSubFolder() {#getCacheSubFolder--}
```
public final String getCacheSubFolder()
```


Подпапка, добавляемая к пути кэша.

**Returns:**
java.lang.String - подпапка, которую следует добавить.
### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public final void set(String key, Object value)
```


Сериализует данные на локальный диск.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Уникальный идентификатор записи кэша. |
| value | java.lang.Object | Объект для сериализации. |

### <T>get(String key, Class<T> clazz) {#-T-get-java.lang.String-java.lang.Class-T--}
```
public final T <T>get(String key, Class<T> clazz)
```


Десериализует данные, связанные с этим ключом, если они присутствуют.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| key | java.lang.String | Ключ, идентифицирующий запрашиваемую запись. |
| clazz | java.lang.Class<T> | Класс ожидаемого значения. |

**Returns:**
T - найденное значение или null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public final List<String> getKeys(String filter)
```


Возвращает все имена файлов, содержащие фильтр в имени файла.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| filter | java.lang.String | Фильтр для использования. |

**Returns:**
java.util.List<java.lang.String> - Имена файлов, содержащие фильтр в имени файла.
