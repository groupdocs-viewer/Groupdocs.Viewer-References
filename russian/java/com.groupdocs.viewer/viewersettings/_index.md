---
title: "ViewerSettings"
second_title: "Справочник API GroupDocs.Viewer для Java"
description: "Определяет параметры для настройки поведения компонента Viewer."
type: docs
weight: 13
url: /ru/java/com.groupdocs.viewer/viewersettings/
---
**Inheritance:**
java.lang.Object
```
public class ViewerSettings
```

Определяет параметры для настройки поведения компонента Viewer.


Класс ViewerSettings предоставляет параметры и свойства для настройки поведения компонента GroupDocs.Viewer во время процесса рендеринга документа.
Вы можете использовать этот класс для указания различных настроек, таких как журналировщик, пользовательская реализация кэша и многое другое.


Пример использования:

````

 final ViewerSettings viewerSettings = new ViewerSettings();
 viewerSettings.setLogger(new ConsoleLogger(false, true));

 try (Viewer viewer = new Viewer("source.pdf", viewerSettings)) {
     // Document processing
 }
 
````


## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [ViewerSettings(Cache cache, ILogger logger)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-) | Инициализирует новый экземпляр |
ViewerSettings
класса.
|
|  | [ViewerSettings(ILogger logger)](#ViewerSettings-com.groupdocs.foundation.logging.ILogger-) | Инициализирует новый экземпляр |
ViewerSettings
класса.
|
|  | [ViewerSettings(Cache cache)](#ViewerSettings-com.groupdocs.viewer.caching.Cache-) | Инициализирует новый экземпляр |
ViewerSettings
класса.
|
|  | [ViewerSettings()](#ViewerSettings--) | Инициализирует новый экземпляр |
ViewerSettings
класса.
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getLogger()](#getLogger--) | Получает реализацию журналировщика, используемую для журналирования (Errors, Warnings, Traces). |
|
|  | [setLogger(ILogger logger)](#setLogger-com.groupdocs.foundation.logging.ILogger-) | Устанавливает реализацию журналировщика, используемую для журналирования (Errors, Warnings, Traces). |
|
|  | [getCache()](#getCache--) | Получает реализацию кэша, используемую для хранения результатов рендеринга. |
|
|  | [setCache(Cache cache)](#setCache-com.groupdocs.viewer.caching.Cache-) | Устанавливает реализацию кэша, используемую для хранения результатов рендеринга. |
|
### ViewerSettings(Cache cache, ILogger logger) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(Cache cache, ILogger logger)
```


Инициализирует новый экземпляр
ViewerSettings
класса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Кеш. |
|
|  | логгер | com.groupdocs.foundation.logging.ILogger | Журналировщик. |
|

### ViewerSettings(ILogger logger) {#ViewerSettings-com.groupdocs.foundation.logging.ILogger-}
```
public ViewerSettings(ILogger logger)
```


Инициализирует новый экземпляр
ViewerSettings
класса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | логгер | com.groupdocs.foundation.logging.ILogger | Журналировщик. |
|

### ViewerSettings(Cache cache) {#ViewerSettings-com.groupdocs.viewer.caching.Cache-}
```
public ViewerSettings(Cache cache)
```


Инициализирует новый экземпляр
ViewerSettings
класса.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Кеш. |
|

### ViewerSettings() {#ViewerSettings--}
```
public ViewerSettings()
```


Инициализирует новый экземпляр
ViewerSettings
класса.


### getLogger() {#getLogger--}
```
public ILogger getLogger()
```


Получает реализацию журналировщика, используемую для журналирования (Errors, Warnings, Traces).


**Returns:**
com.groupdocs.foundation.logging.ILogger - реализация журналировщика.

### setLogger(ILogger logger) {#setLogger-com.groupdocs.foundation.logging.ILogger-}
```
public void setLogger(ILogger logger)
```


Устанавливает реализацию журналировщика, используемую для журналирования (Errors, Warnings, Traces).


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | логгер | com.groupdocs.foundation.logging.ILogger | Реализация журналировщика для установки. |
|

### getCache() {#getCache--}
```
public final Cache getCache()
```


Получает реализацию кэша, используемую для хранения результатов рендеринга.


**Returns:**
[Cache](../../com.groupdocs.viewer.caching/cache) - the cache implementation.

### setCache(Cache cache) {#setCache-com.groupdocs.viewer.caching.Cache-}
```
public void setCache(Cache cache)
```


Устанавливает реализацию кэша, используемую для хранения результатов рендеринга.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | cache | [Cache](../../com.groupdocs.viewer.caching/cache) | Реализация кэша. |
|

